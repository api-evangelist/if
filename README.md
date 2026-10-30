# IF

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

Integrated Finance (IF) is a modular fintech infrastructure platform — a "financial operating system" — that lets companies build banking, card, and payment experiences for their users without becoming a bank. Its orchestration layers (IF API interface, IF CORE workflow, IF CONNECT integration) sit on top of multiple banking, card-issuing, FX, and compliance providers and expose a single REST API covering clients and users, real / virtual / shared-pool accounts, incoming and outgoing bank transfers, currency exchanges, card issuing and processing (including 3DS and PIN management), beneficiary verification, generic transactions, and open-banking consents. Authentication is OAuth 2.0 on Keycloak (JWT client assertion, client_credentials); the API supports idempotency on all POST endpoints, Ed25519-signed webhooks with automatic retry, and a full sandbox environment for testing.

**Areas:** Company · Financial Services · Embedded Finance · Banking as a Service · Payments · Cards · Foreign Exchange · Compliance · Open Banking

## IF on APIs.io

Everything profiled for IF is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/if/](https://apis.io/providers/if/)** — or go straight to one of the APIs or properties below.

### APIs (29)

- [Integrated Finance API](https://apis.io/apis/if/integrated-finance-api/) — Single REST API for the Integrated Finance platform — clients, users, real / virtual / shared-pool accounts, bank transfers, currency exchanges, card…
- [IF Account Statements API](https://apis.io/apis/if/if-account-statements-api/) — The Account Statements API from IF — 4 operation(s) for account statements.
- [IF Accounts API](https://apis.io/apis/if/if-accounts-api/) — The Accounts API from IF — 3 operation(s) for accounts.
- [IF Balance Adjustments API](https://apis.io/apis/if/if-balance-adjustments-api/) — The Balance Adjustments API from IF — 1 operation(s) for balance adjustments.
- [IF Beneficiaries API](https://apis.io/apis/if/if-beneficiaries-api/) — The Beneficiaries API from IF — 2 operation(s) for beneficiaries.
- [IF Beneficiary Bank Accounts API](https://apis.io/apis/if/if-beneficiary-bank-accounts-api/) — The Beneficiary Bank Accounts API from IF — 2 operation(s) for beneficiary bank accounts.
- [IF Beneficiary Bank Accounts Metadata API](https://apis.io/apis/if/if-beneficiary-bank-accounts-metadata-api/) — The Beneficiary Bank Accounts Metadata API from IF — 1 operation(s) for beneficiary bank accounts metadata.
- [IF Beneficiary Verifications API](https://apis.io/apis/if/if-beneficiary-verifications-api/) — The Beneficiary Verifications API from IF — 1 operation(s) for beneficiary verifications.
- [IF Card Transaction Authentications API](https://apis.io/apis/if/if-card-transaction-authentications-api/) — The Card Transaction Authentications API from IF — 2 operation(s) for card transaction authentications.
- [IF Card Transactions API](https://apis.io/apis/if/if-card-transactions-api/) — The Card Transactions API from IF — 2 operation(s) for card transactions.
- [IF Cards API](https://apis.io/apis/if/if-cards-api/) — The Cards API from IF — 5 operation(s) for cards.
- [IF Client Relations API](https://apis.io/apis/if/if-client-relations-api/) — The Client Relations API from IF — 2 operation(s) for client relations.
- [IF Clients API](https://apis.io/apis/if/if-clients-api/) — The Clients API from IF — 2 operation(s) for clients.
- [IF Direct Debit Mandates API](https://apis.io/apis/if/if-direct-debit-mandates-api/) — The Direct Debit Mandates API from IF — 2 operation(s) for direct debit mandates.
- [IF Direct Debit Payments API](https://apis.io/apis/if/if-direct-debit-payments-api/) — The Direct Debit Payments API from IF — 2 operation(s) for direct debit payments.
- [IF Exchange Quotes API](https://apis.io/apis/if/if-exchange-quotes-api/) — The Exchange Quotes API from IF — 2 operation(s) for exchange quotes.
- [IF Exchange Transactions API](https://apis.io/apis/if/if-exchange-transactions-api/) — The Exchange Transactions API from IF — 2 operation(s) for exchange transactions.
- [IF Generic Transactions API](https://apis.io/apis/if/if-generic-transactions-api/) — The Generic Transactions API from IF — 2 operation(s) for generic transactions.
- [IF Incoming Transfers API](https://apis.io/apis/if/if-incoming-transfers-api/) — The Incoming Transfers API from IF — 2 operation(s) for incoming transfers.
- [IF Incoming Transfers - Compliance API](https://apis.io/apis/if/if-incoming-transfers-compliance-api/) — The Incoming Transfers - Compliance API from IF — 1 operation(s) for incoming transfers - compliance.
- [IF Open Banking Consents API](https://apis.io/apis/if/if-open-banking-consents-api/) — The Open Banking Consents API from IF — 2 operation(s) for open banking consents.
- [IF Outgoing Transfers API](https://apis.io/apis/if/if-outgoing-transfers-api/) — The Outgoing Transfers API from IF — 2 operation(s) for outgoing transfers.
- [IF Outgoing Transfers - Compliance API](https://apis.io/apis/if/if-outgoing-transfers-compliance-api/) — The Outgoing Transfers - Compliance API from IF — 1 operation(s) for outgoing transfers - compliance.
- [IF Outgoing Transfers Metadata API](https://apis.io/apis/if/if-outgoing-transfers-metadata-api/) — The Outgoing Transfers Metadata API from IF — 2 operation(s) for outgoing transfers metadata.
- [IF Provisioned Account Credits API](https://apis.io/apis/if/if-provisioned-account-credits-api/) — The Provisioned Account Credits API from IF — 2 operation(s) for provisioned account credits.
- [IF Transaction Accounts API](https://apis.io/apis/if/if-transaction-accounts-api/) — The Transaction Accounts API from IF — 2 operation(s) for transaction accounts.
- [IF User & Client Relations API](https://apis.io/apis/if/if-user-client-relations-api/) — The User & Client Relations API from IF — 2 operation(s) for user & client relations.
- [IF User Invitations API](https://apis.io/apis/if/if-user-invitations-api/) — The User Invitations API from IF — 2 operation(s) for user invitations.
- [IF Users API](https://apis.io/apis/if/if-users-api/) — The Users API from IF — 2 operation(s) for users.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [If Webhooks](https://apis.io/asyncapis/if/if-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [if](https://apis.io/servers/if/if/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [If Agentic Access](https://apis.io/agentic-access/if/if-agentic-access/)

#### JSON Schema (60)

The data models the API reads and writes.

- [AccountAdjustmentCreateRequest](https://apis.io/schemas/if/if-account-adjustment-create-request/)
- [AccountAdjustmentCreateResponse](https://apis.io/schemas/if/if-account-adjustment-create-response/)
- [AccountCreateRequest](https://apis.io/schemas/if/if-account-create-request/)
- [AccountDepositInformationResponse](https://apis.io/schemas/if/if-account-deposit-information-response/)
- [AccountOpenBankingConsentUpdateRequest](https://apis.io/schemas/if/if-account-open-banking-consent-update-request/)
- [AccountOpenBankingConsentUpdateResponse](https://apis.io/schemas/if/if-account-open-banking-consent-update-response/)
- [AccountStatementsListRequest](https://apis.io/schemas/if/if-account-statements-list-request/)
- [AccountStatementsListResponse](https://apis.io/schemas/if/if-account-statements-list-response/)
- [BeneficiaryBankAccountUpdateRequest](https://apis.io/schemas/if/if-beneficiary-bank-account-update-request/)
- [BeneficiaryBankAccountUpdateResponse](https://apis.io/schemas/if/if-beneficiary-bank-account-update-response/)
- [BeneficiaryVerificationRequest](https://apis.io/schemas/if/if-beneficiary-verification-request/)
- [BeneficiaryVerificationResponse](https://apis.io/schemas/if/if-beneficiary-verification-response/)
- [CardAccountCreateRequest](https://apis.io/schemas/if/if-card-account-create-request/)
- [CardAccountCreateResponse](https://apis.io/schemas/if/if-card-account-create-response/)
- [CardAccountDeleteResponse](https://apis.io/schemas/if/if-card-account-delete-response/)
- [CardAccountListResponse](https://apis.io/schemas/if/if-card-account-list-response/)
- [CardOTPCreateRequest](https://apis.io/schemas/if/if-card-otpcreate-request/)
- [CardOTPCreateResponse](https://apis.io/schemas/if/if-card-otpcreate-response/)
- [CardTransactionAuthenticationGetResponse](https://apis.io/schemas/if/if-card-transaction-authentication-get-response/)
- [CardTransactionAuthenticationListResponse](https://apis.io/schemas/if/if-card-transaction-authentication-list-response/)
- [CardTransactionAuthenticationUpdateRequest](https://apis.io/schemas/if/if-card-transaction-authentication-update-request/)
- [CardTransactionAuthenticationUpdateResponse](https://apis.io/schemas/if/if-card-transaction-authentication-update-response/)
- [CardTransactionGetResponse](https://apis.io/schemas/if/if-card-transaction-get-response/)
- [CardTransactionListResponse](https://apis.io/schemas/if/if-card-transaction-list-response/)
- [ClientRelationCreateRequest](https://apis.io/schemas/if/if-client-relation-create-request/)
- …and 35 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [If Context](https://apis.io/jsonld/if/if-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [IF API Rules](https://apis.io/rules/if/if-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [If Authentication](https://apis.io/security/if/if-authentication/)
- [If Domain Security](https://apis.io/security/if/if-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [If Scopes](https://apis.io/scopes/if/if-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://integrated.finance)
- [Documentation](https://developer.integrated.finance/docs)
- [Getting started](https://developer.integrated.finance/docs/getting-started)
- [API reference](https://developer.integrated.finance/reference)
- [Support](https://integrated.finance/support)
- [Blog](https://integrated.finance/insights)
- [Compliance](https://integrated.finance/security-policy)
- [Terms of service](https://integrated.finance/terms-and-conditions)
- [Privacy policy](https://integrated.finance/privacy-policy)
- [GitHub](https://github.com/integrated-finance)
- [Status](https://integratedfinance.statuspage.io)

## API Evangelist rating

**Kin Score 52.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.4 |
| Contract quality | 61.2 |
| Contract governance | 33.3 |
| Operational transparency | 50.0 |
| Developer ergonomics | 51.2 |
| Access clarity | 28.9 |

**Agent readiness 41.9** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 42.9** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/if/](https://apis.io/providers/if/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for IF: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/if/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
