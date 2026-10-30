# Nasdaq

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

Nasdaq, Inc. operates the Nasdaq stock exchanges and sells market data, index, and financial technology products. Its developer surface is Nasdaq Data Link (data.nasdaq.com): a Tables API (REST, api_key, JSON/XML/CSV, 10,000-row pages with cursor and bulk export), a Bulk Download API, a request-based REST API for real-time and delayed equities, indexes, ETPs and options (Nasdaq Cloud Data Service, OAuth client-credentials, customer-specific base URL), and a Kafka-based Streaming API delivered through first-party Java and Python SDKs.

**Areas:** Data Marketplace · Financial Data · Fortune 1000 · Kafka · Market Data · Stock Exchange · Streaming

## Nasdaq on APIs.io

Everything profiled for Nasdaq is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/nasdaq/](https://apis.io/providers/nasdaq/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Nasdaq Cloud Data Service (NCDS) — Kafka Streams](https://apis.io/apis/nasdaq/nasdaq-cloud-data-service-ncds-kafka-streams/) — Real-time Nasdaq market data delivered over Apache Kafka (TLS) with SASL/OAUTHBEARER authentication against a Keycloak pro-realm token endpoint. Topics…
- [Nasdaq Data Link Tables API](https://apis.io/apis/nasdaq/nasdaq-data-link-tables-api/) — REST access to Nasdaq Data Link tabular datasets: GET /api/v3/datatables/{datatable_code}.{format} with row and column filters (qopts.columns), cursor…
- [Nasdaq Data Link Bulk Download API](https://apis.io/apis/nasdaq/nasdaq-data-link-bulk-download-api/) — Asynchronous bulk download of Nasdaq Data Link tables: GET /api/v1/bulkdownloads/{datatable_code} with row filters returns a job (PENDING, RUNNING,…
- [Nasdaq Cloud Data Service (NCDS) REST API](https://apis.io/apis/nasdaq/nasdaq-cloud-data-service-ncds-rest-api/) — Request-based REST API for real-time and delayed Nasdaq, BX, PSX and CQT equities (last sale, last trade, last quote, snapshot, trends, bars), indexes, ETPs…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Nasdaq Cloud Data Service (NCDS) — Kafka Streams](https://apis.io/asyncapis/nasdaq/nasdaq-asyncapi/)

#### Event channels (8)

Individual events and webhooks the provider emits.

- [{entitledTopic}](https://apis.io/channels/nasdaq/entitledtopic/)
- [GIDS](https://apis.io/channels/nasdaq/gids/)
- [NEWS-PRO-GLOBAL](https://apis.io/channels/nasdaq/news-pro-global/)
- [NLSCTA](https://apis.io/channels/nasdaq/nlscta/)
- [NLSPLUS-CTA-V4](https://apis.io/channels/nasdaq/nlsplus-cta-v4/)
- [NLSPLUS-UTP-V4](https://apis.io/channels/nasdaq/nlsplus-utp-v4/)
- [NLSUTP](https://apis.io/channels/nasdaq/nlsutp/)
- [UTPBIN-UF30](https://apis.io/channels/nasdaq/utpbin-uf30/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Nasdaq — asyncapi rules](https://apis.io/rules/nasdaq/nasdaq-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Nasdaq Authentication](https://apis.io/security/nasdaq/nasdaq-authentication/)
- [Nasdaq Domain Security](https://apis.io/security/nasdaq/nasdaq-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Nasdaq Plans Pricing](https://apis.io/plans/nasdaq/nasdaq-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Nasdaq Rate Limits](https://apis.io/rate-limits/nasdaq/nasdaq-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.nasdaq.com/)
- [Documentation](https://www.nasdaq.com/products/data/data-link/api)
- [Privacy policy](https://www.nasdaq.com/privacy-statement)
- [GitHub](https://github.com/Nasdaq)
- [Status](https://status.data.nasdaq.com/)

## API Evangelist rating

**Kin Score 39.0** — thin · rubric 0.24.0 · scored 2026-10-20

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 46.9 |
| Contract governance | 13.6 |
| Operational transparency | 50.0 |
| Developer ergonomics | 52.4 |
| Access clarity | 10.5 |

**Agent readiness 24.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.4** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/nasdaq/](https://apis.io/providers/nasdaq/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nasdaq: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/nasdaq/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
