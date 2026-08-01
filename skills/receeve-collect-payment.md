---
name: Offer instalments or a settlement and collect payment
description: Set up an instalment plan or apply a settlement and reconcile the payment on a claim.
api: openapi/receeve-openapi-original.yml
operations: [getInstalmentPlanDefinitions, createInstalmentPlan, setSettlementDefinition, applySettlement, MatchAccountPayment]
---

# Offer instalments or a settlement and collect payment

## Steps
1. Authenticate (see receeve-authenticate.md).
2. Offer instalments: **`getInstalmentPlanDefinitions`** (`GET /finance/v1/{clientId}/instalment_plan_definitions`)
   to list available plans, then **`createInstalmentPlan`** (`POST /finance/v1/{clientId}/create_instalment_plan`)
   for the debtor.
3. Or offer a settlement: **`setSettlementDefinition`** (`POST /finance/v1/{clientId}/set_settlement_definition`)
   then **`applySettlement`** (`POST /finance/v1/{clientId}/apply_settlement`). Pass a unique
   `applicationRef` — it is the idempotency key, so retries with the same value are safe.
4. Reconcile an incoming payment with **`MatchAccountPayment`**
   (`POST /v1/{clientId}/match_account_payment`).
5. Confirm via webhooks: `event.instalmentPlan.created`, `event.promiseToPay.resolved`,
   `event.claimDebtPayment.settled`, `event.claim.resolved`.

## Rules
- `applySettlement` is idempotent on `applicationRef`; reuse it on retry rather than
  re-computing to avoid double-applying.
- Financial write failures surface on a `200` with `success: false` — check the envelope.
- See conventions/receeve-conventions.yml.
