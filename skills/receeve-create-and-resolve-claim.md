---
name: Create, track and resolve a collections claim
description: Import an account, raise a claim, watch it via webhooks, then resolve it.
api: openapi/receeve-openapi-original.yml
operations: [createAccounts, createClaims, getAccountClaims, resolveClaims]
---

# Create, track and resolve a collections claim

## Steps
1. Authenticate (see receeve-authenticate.md).
2. **`createAccounts`** — `POST /v1/{clientId}/create_accounts` to register the debtor
   account with its debtors, ledger entries and products.
3. **`createClaims`** — `POST /v1/{clientId}/create_claims`. Required fields:
   `currency`, `originalDueDate`, `currentDueDate`, `amount`, `primaryDebtor` details,
   `country`. A duplicate returns `[4002] ParameterInputError: Claim already exists`.
4. Track progress by subscribing to webhooks (`event.claim.created`,
   `event.claimDebtPayment.settled`, `event.strategy.*`) — verify each payload's
   RSA/SHA-256 signature and de-dupe on `messageId`.
5. Inspect state anytime with **`getAccountClaims`** — `GET /v1/{clientId}/get_account_claims`.
6. **`resolveClaims`** — `POST /v1/{clientId}/resolve_claims` with `ref` and a valid
   `reason`: one of `CLAIM_SOLD`, `CLAIM_PAID`, `FRAUDULENT`, `CLAIM_DISCARDED`,
   `CLAIM_DISCHARGED`, `CLAIM_INVALIDATED`.

## Rules
- Business failures come back on a `200` with `{ success: false, messages: [...] }` — always
  check `success`, do not rely on HTTP status alone.
- See conventions/receeve-conventions.yml and errors/receeve-error-codes.yml.
