# Peeve

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

Peeve provides an AI‑powered customer support agent platform for SaaS companies. It automates answering, showing, doing, and hand‑off tasks through a multi‑modal interface, offering analytics, intent detection, and connector integrations. The service emphasizes privacy, security, and a managed control plane (MCP) for enterprise workflows, with transparent pricing and extensive documentation.

**Areas:** AI Customer Support · SaaS · In‑app Help · Backend Integration · Analytics

## Peeve on APIs.io

Everything profiled for Peeve is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/peeve-ai/](https://apis.io/providers/peeve-ai/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Peeve Analytics API](https://apis.io/apis/peeve-ai/peeve-ai-analytics-api/) — Usage and satisfaction results.
- [Peeve Ask API](https://apis.io/apis/peeve-ai/peeve-ai-ask-api/) — Ask the agent a question from your backend and get a grounded answer.
- [Peeve Configuration API](https://apis.io/apis/peeve-ai/peeve-ai-configuration-api/) — Guardrails and the kill switch.
- [Peeve Contacts API](https://apis.io/apis/peeve-ai/peeve-ai-contacts-api/) — Everyone Peeve knows about: **users** your product identified, and anonymous **visitors**. Filter with `?kind=`.
- [Peeve Hand Offs API](https://apis.io/apis/peeve-ai/peeve-ai-hand-offs-api/) — Hand-offs to a human, and their status.
- [Peeve Leads API](https://apis.io/apis/peeve-ai/peeve-ai-leads-api/) — Visitors the agent qualified. Read and re-status only — capture happens through Peeve's own channels.
- [Peeve Meetings API](https://apis.io/apis/peeve-ai/peeve-ai-meetings-api/) — Meetings booked through the agent.
- [Peeve Sessions API](https://apis.io/apis/peeve-ai/peeve-ai-sessions-api/) — Agent conversations and their transcripts.
- [Peeve Users API](https://apis.io/apis/peeve-ai/peeve-ai-users-api/) — Push your identified users into Peeve from your backend.
- [Peeve Webhooks API](https://apis.io/apis/peeve-ai/peeve-ai-webhooks-api/) — Register and manage the endpoints Peeve delivers events to. Equivalent to the Connectors UI — an endpoint created here is the same row, with the same…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Peeve Ai Webhooks](https://apis.io/asyncapis/peeve-ai/peeve-ai-webhooks/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Peeve Agentic Access](https://apis.io/agentic-access/peeve-ai/peeve-ai-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [ListEnvelope](https://apis.io/schemas/peeve-ai/peeve-ai-list-envelope/)
- [SessionObject](https://apis.io/schemas/peeve-ai/peeve-ai-session-object/)
- [UsageObject](https://apis.io/schemas/peeve-ai/peeve-ai-usage-object/)
- [UserPush](https://apis.io/schemas/peeve-ai/peeve-ai-user-push/)
- [VendorTokenObject](https://apis.io/schemas/peeve-ai/peeve-ai-vendor-token-object/)
- [WebhookEndpointWithSecret](https://apis.io/schemas/peeve-ai/peeve-ai-webhook-endpoint-with-secret/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Peeve Ai Context](https://apis.io/jsonld/peeve-ai/peeve-ai-context/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Peeve Openapi Overlay](https://apis.io/overlays/peeve-ai/peeve-ai-openapi-overlay/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Peeve API Rules](https://apis.io/rules/peeve-ai/peeve-ai-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Peeve Authentication](https://apis.io/security/peeve-ai/peeve-ai-authentication/)
- [Peeve Domain Security](https://apis.io/security/peeve-ai/peeve-ai-domain-security/)
- [Peeve Trust Center](https://apis.io/security/peeve-ai/peeve-ai-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Peeve Plans Pricing](https://apis.io/plans/peeve-ai/peeve-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Peeve Rate Limits](https://apis.io/rate-limits/peeve-ai/peeve-ai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://peeve.ai)
- [Documentation](https://docs.peeve.ai/api/overview)
- [Getting started](https://docs.peeve.ai/get-started/quickstart)
- [Pricing](https://peeve.ai/pricing)
- [Support](https://peeve.ai/solutions/support)
- [Changelog](https://peeve.ai/changelog/)
- [Blog](https://peeve.ai/blog)
- [Security](https://peeve.ai/product/security/)
- [Compliance](https://peeve.ai/trust/)
- [Terms of service](https://peeve.ai/legal/terms)
- [Privacy policy](https://peeve.ai/legal/privacy)
- [GitHub](https://github.com/peeveai)

## API Evangelist rating

**Kin Score 73.0** — exemplar · rubric 0.27.0 · scored 2026-11-13

| Facet | Score |
|---|---|
| Discoverability | 67.9 |
| Contract quality | 68.6 |
| Contract governance | 79.1 |
| Operational transparency | 67.9 |
| Developer ergonomics | 54.0 |
| Access clarity | 88.9 |

**Agent readiness 69.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/peeve-ai/](https://apis.io/providers/peeve-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Peeve: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/peeve-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
