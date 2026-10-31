# Receeve

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Receeve is a no-code debt collection and receivables management SaaS platform, founded in Hamburg, Germany and backed by Speedinvest. It was acquired by InDebted and now operates as the "Receive" product — a debt servicing platform that lets creditors, banks, lenders, utilities and collection agencies automate the full collections lifecycle: importing accounts and claims, running configurable dunning strategies and journeys, sending multi-channel communications (email, SMS, letters, calls), generating hosted debtor landing pages, and reconciling payments, promises-to-pay, instalment plans and settlements. The Receive Client API is an OpenAPI 3.0 REST API secured with OAuth2 client-credentials (Bearer tokens) and emits an extensive catalog of signed webhooks for account, claim, communication, finance, landing-page and strategy events.

**Areas:** Company · Debt Collection · Receivables Management · Debt Servicing · Collection · Fintech · Payments · Webhook · Financial Services · Dunning

## Receeve on APIs.io

Everything profiled for Receeve is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/receeve/](https://apis.io/providers/receeve/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Receeve Account API](https://apis.io/apis/receeve/receeve-account-api/) — A formal business arrangement providing for regular dealings or services (such as banking, advertising, or store credit) and involving the establishment and…
- [Receeve AccountMandate API](https://apis.io/apis/receeve/receeve-accountmandate-api/) — The AccountMandate API from Receeve — 3 operation(s) for accountmandate.
- [Receeve Claim API](https://apis.io/apis/receeve/receeve-claim-api/) — A claim is an outstanding payment that is owed. You can always update this balance if multiple payments are missed and you want to aggregate the amounts.
- [Receeve CustomTriggers API](https://apis.io/apis/receeve/receeve-customtriggers-api/) — The CustomTriggers API from Receeve — 1 operation(s) for customtriggers.
- [Receeve Debtor API](https://apis.io/apis/receeve/receeve-debtor-api/) — The Debtor API from Receeve — 1 operation(s) for debtor.
- [Receeve Event API](https://apis.io/apis/receeve/receeve-event-api/) — Event that happened in Receive systems, for example, claim created or email delivered.
- [Receeve Files API](https://apis.io/apis/receeve/receeve-files-api/) — The Files API from Receeve — 1 operation(s) for files.
- [Receeve Finance Instalments V2 API](https://apis.io/apis/receeve/receeve-finance-instalments-v2-api/) — The Finance Instalments V2 API from Receeve — 5 operation(s) for finance instalments v2.
- [Receeve Finance Settlements API](https://apis.io/apis/receeve/receeve-finance-settlements-api/) — The Finance Settlements API from Receeve — 5 operation(s) for finance settlements.
- [Receeve Journey API](https://apis.io/apis/receeve/receeve-journey-api/) — This is the overall strategy to resolve the outstanding payment or debt.
- [Receeve Message API](https://apis.io/apis/receeve/receeve-message-api/) — Communication message in .eml format that was sent to Debtor.
- [Receeve PromiseToPay API](https://apis.io/apis/receeve/receeve-promisetopay-api/) — The PromiseToPay API from Receeve — 1 operation(s) for promisetopay.
- [Receeve Security API](https://apis.io/apis/receeve/receeve-security-api/) — The Security API from Receeve — 1 operation(s) for security.
- [Receeve Landing Page API](https://apis.io/apis/receeve/receeve-landing-page-api/) — The Landing Page of the Debtor, used to display, pay the Claims (or other use cases).

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Receive (Receeve) Webhook Events](https://apis.io/asyncapis/receeve/receeve-webhooks-asyncapi/)

#### Event channels (76)

Individual events and webhooks the provider emits.

- [event.accountAmountTotalFees.updated](https://apis.io/channels/receeve/event-accountamounttotalfees-updated/)
- [event.accountDebtor.updated](https://apis.io/channels/receeve/event-accountdebtor-updated/)
- [event.accountDebtorUpdate.failed](https://apis.io/channels/receeve/event-accountdebtorupdate-failed/)
- [event.accountInvoiceLedgerEntriesDueDateUpdate.failed](https://apis.io/channels/receeve/event-accountinvoiceledgerentriesduedateupdate-failed/)
- [event.accountLedgerEntries.added](https://apis.io/channels/receeve/event-accountledgerentries-added/)
- [event.accountLedgerEntriesAdding.failed](https://apis.io/channels/receeve/event-accountledgerentriesadding-failed/)
- [event.accountMeta.set](https://apis.io/channels/receeve/event-accountmeta-set/)
- [event.accountMetaSet.failed](https://apis.io/channels/receeve/event-accountmetaset-failed/)
- [event.claim.created](https://apis.io/channels/receeve/event-claim-created/)
- [event.claim.resolved](https://apis.io/channels/receeve/event-claim-resolved/)
- [event.claimDebtPayment.processing](https://apis.io/channels/receeve/event-claimdebtpayment-processing/)
- [event.claimDebtPayment.settled](https://apis.io/channels/receeve/event-claimdebtpayment-settled/)
- [event.claimMeta.updated](https://apis.io/channels/receeve/event-claimmeta-updated/)
- [event.claimTotalAmount.updated.v1](https://apis.io/channels/receeve/event-claimtotalamount-updated-v1/)
- [event.customClaimTrigger.executed](https://apis.io/channels/receeve/event-customclaimtrigger-executed/)
- [event.debtorCallCommunicationResolution.received](https://apis.io/channels/receeve/event-debtorcallcommunicationresolution-received/)
- [event.debtorEmail.delivered](https://apis.io/channels/receeve/event-debtoremail-delivered/)
- [event.debtorEmail.opened](https://apis.io/channels/receeve/event-debtoremail-opened/)
- [event.debtorEmail.queued](https://apis.io/channels/receeve/event-debtoremail-queued/)
- [event.debtorEmailCommunicationResolution.received](https://apis.io/channels/receeve/event-debtoremailcommunicationresolution-received/)
- [event.debtorEmailDelivery.failed](https://apis.io/channels/receeve/event-debtoremaildelivery-failed/)
- [event.debtorEmailDelivery.interrupted](https://apis.io/channels/receeve/event-debtoremaildelivery-interrupted/)
- [event.debtorEmailProcessing.failed](https://apis.io/channels/receeve/event-debtoremailprocessing-failed/)
- [event.debtorEmailUnsubscribe.requested](https://apis.io/channels/receeve/event-debtoremailunsubscribe-requested/)
- [event.debtorLetter.generated](https://apis.io/channels/receeve/event-debtorletter-generated/)
- …and 51 more published on APIs.io

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [receeve](https://apis.io/servers/receeve/receeve/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Receeve Agentic Access](https://apis.io/agentic-access/receeve/receeve-agentic-access/)

#### Collections (14)

Postman and Open Collection request collections.

- [InDebted Receive API Documentation Account API](https://apis.io/collections/receeve/open-receeve-account-api/)
- [InDebted Receive API Documentation Account AccountMandate API](https://apis.io/collections/receeve/open-receeve-accountmandate-api/)
- [InDebted Receive API Documentation Account Claim API](https://apis.io/collections/receeve/open-receeve-claim-api/)
- [InDebted Receive API Documentation Account CustomTriggers API](https://apis.io/collections/receeve/open-receeve-customtriggers-api/)
- [InDebted Receive API Documentation Account Debtor API](https://apis.io/collections/receeve/open-receeve-debtor-api/)
- [InDebted Receive API Documentation Account Event API](https://apis.io/collections/receeve/open-receeve-event-api/)
- [InDebted Receive API Documentation Account Files API](https://apis.io/collections/receeve/open-receeve-files-api/)
- [InDebted Receive API Documentation Account Finance Instalments V2 API](https://apis.io/collections/receeve/open-receeve-finance-instalments-v2-api/)
- [InDebted Receive API Documentation Account Finance Settlements API](https://apis.io/collections/receeve/open-receeve-finance-settlements-api/)
- [InDebted Receive API Documentation Account Journey API](https://apis.io/collections/receeve/open-receeve-journey-api/)
- [InDebted Receive API Documentation Account LandingPage API](https://apis.io/collections/receeve/open-receeve-landingpage-api/)
- [InDebted Receive API Documentation Account Message API](https://apis.io/collections/receeve/open-receeve-message-api/)
- [InDebted Receive API Documentation Account PromiseToPay API](https://apis.io/collections/receeve/open-receeve-promisetopay-api/)
- [InDebted Receive API Documentation Account Security API](https://apis.io/collections/receeve/open-receeve-security-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Receeve Openapi Overlay](https://apis.io/overlays/receeve/receeve-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Receeve Authentication](https://apis.io/security/receeve/receeve-authentication/)
- [Receeve Domain Security](https://apis.io/security/receeve/receeve-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://receeve.com)
- [Documentation](https://docs.indebted.co/docs/receive/)
- [Getting started](https://docs.indebted.co/docs/receive/integration/tl-dr)
- [API reference](https://api.receeve.com/api-reference)
- [Blog](https://www.indebted.co/newsroom)
- [Trust centre](https://trust.indebted.co/)

## API Evangelist rating

**Kin Score 33.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 55.1 |
| Contract governance | 4.5 |
| Operational transparency | 7.9 |
| Developer ergonomics | 35.1 |
| Access clarity | 7.9 |

**Agent readiness 32.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.6** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/receeve/](https://apis.io/providers/receeve/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Receeve: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/receeve/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
