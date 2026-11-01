# University of Illinois Urbana-Champaign

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

The University of Illinois Urbana-Champaign (UIUC) is the public land-grant flagship of the University of Illinois System and a founding Big Ten institution. It is one of the few universities in this cohort that genuinely ENGINEERS a public API estate rather than buying one: the Rokwire platform behind the official Illinois app is UIUC's own open-source work, published under Apache 2.0 in github.com/rokwire and deployed on the institution's own host at api.rokwire.illinois.edu, where nine building blocks answer an unauthenticated /version endpoint and two of them (Core 1.62.0, Gateway 2.21.1) publish OpenAPI 3.0 through Swagger UI. Around it sit four more institution-operated machine-readable surfaces: the Course Information Suite (CISAPI) Course Explorer, which serves class schedule and catalog XML with no authentication; the IDEALS institutional repository's OAI-PMH 2.0 endpoint, running on Illinois Library's own Rails application rather than a vendor platform; the Illinois Data Bank, an in-house research data repository that has minted 1,306 DataCite DOIs under prefix 10.13012 and exposes its catalog as JSON; and the campus Shibboleth identity provider, registered in InCommon as urn:mace:incommon:uiuc.edu. The estate is real but uneven — errors are documented in prose with no schemas, no deprecation policy or Sunset header exists anywhere, seven live Rokwire building blocks ship no contract at all, and illinois.edu answers /llms.txt and /.well-known/security.txt with a soft-404 that returns HTTP 200. Research profiles (Illinois Experts / Elsevier Pure) and library discovery (Ex Libris Primo) are vendor platforms recorded here as tenant relationships: the data is the university's, the contract is not.

**Areas:** University · Higher Education · Education · Public Research University · United States · Illinois · Big Ten · Land-Grant University · Course Catalog · Research Data · Research Repository · Open Data

## University of Illinois Urbana-Champaign on APIs.io

Everything profiled for University of Illinois Urbana-Champaign is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-illinois-urbana-champaign/](https://apis.io/providers/university-of-illinois-urbana-champaign/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Rokwire Core Building Block API](https://apis.io/apis/university-of-illinois-urbana-champaign/rokwire-core-building-block/) — The identity, account and authorization service at the centre of UIUC's Rokwire platform — accounts, profiles, applications, organizations, service…
- [Rokwire Gateway Building Block API](https://apis.io/apis/university-of-illinois-urbana-champaign/rokwire-gateway-building-block/) — The Rokwire service that fronts external and campus systems for the Illinois app — wayfinding and building/floorplan data, campus data streams, and…
- [Course Explorer (CISAPI)](https://apis.io/apis/university-of-illinois-urbana-champaign/cisapi-course-explorer/) — The Course Information Suite API — RESTful resources over Class Schedule and Course Catalog data, organised as Schedule, Catalog, GenEd, Term and Subjects…
- [IDEALS OAI-PMH](https://apis.io/apis/university-of-illinois-urbana-champaign/ideals-oai-pmh/) — The OAI-PMH 2.0 data provider for IDEALS, the Illinois Digital Environment for Access to Learning and Scholarship. Identify reports repositoryName "IDEALS @…
- [Illinois Data Bank Dataset Metadata](https://apis.io/apis/university-of-illinois-urbana-champaign/illinois-data-bank/) — The campus research data repository, built and run in-house by the University Library (github.com/medusa-project/databank, Ruby on Rails) rather than bought…
- [Illinois Shibboleth Identity Provider (InCommon)](https://apis.io/apis/university-of-illinois-urbana-champaign/incommon-shibboleth-idp/) — The campus SAML identity provider — the one surface a university operates by definition and almost never has catalogued.…
- [Illinois Experts (Elsevier Pure)](https://apis.io/apis/university-of-illinois-urbana-champaign/illinois-experts/) — TENANT RELATIONSHIP, not a UIUC contract. Illinois Experts is the university's research information and expert-profile portal, and the data in it — people,…
- [University Library Discovery (Ex Libris Primo)](https://apis.io/apis/university-of-illinois-urbana-champaign/library-discovery/) — TENANT RELATIONSHIP, not a UIUC contract. Library discovery at Illinois runs on Ex Libris Primo — search.library.illinois.edu redirects into…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [University Of Illinois Urbana Champaign Agentic Access](https://apis.io/agentic-access/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Account](https://apis.io/schemas/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-account/)
- [Building](https://apis.io/schemas/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-building/)
- [Organization](https://apis.io/schemas/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-organization/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [University Of Illinois Urbana Champaign Building Structure](https://apis.io/json-structure/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-building-structure/)
- [University Of Illinois Urbana Champaign Organization Structure](https://apis.io/json-structure/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-organization-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Illinois Urbana Champaign Context](https://apis.io/jsonld/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Illinois Urbana-Champaign API Vocabulary](https://apis.io/vocabularies/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-vocabulary/)

#### Examples (2)

Example requests and responses.

- [University Of Illinois Urbana Champaign Building Example](https://apis.io/examples/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-building-example/)
- [University Of Illinois Urbana Champaign Organization Example](https://apis.io/examples/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-organization-example/)

#### Collections (12)

Postman and Open Collection request collections.

- [Rokwire Core Building Block Admin API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-admin-api/)
- [Rokwire Core Building Block Admin BBs API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-bbs-api/)
- [Rokwire Core Building Block Admin Client API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-client-api/)
- [Rokwire Core Building Block Admin Default API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-default-api/)
- [Rokwire Core Building Block Admin Enc API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-enc-api/)
- [Rokwire Core Building Block Admin Services API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-services-api/)
- [Rokwire Core Building Block Admin System API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-system-api/)
- [Rokwire Core Building Block Admin Third-Party Services API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-third-party-services-api/)
- [Rokwire Core Building Block Admin TPS API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-tps-api/)
- [Rokwire Core Building Block Admin UI API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-ui-api/)
- [Rokwire Core Building Block Admin Version API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-version-api/)
- [Rokwire Core Building Block Admin .well Known API](https://apis.io/collections/university-of-illinois-urbana-champaign/open-university-of-illinois-urbana-champaign-well-known-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [University of Illinois Urbana-Champaign — jsonschema rules](https://apis.io/rules/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-jsonschema-spectral-rules/)
- [University of Illinois Urbana-Champaign API Rules](https://apis.io/rules/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Illinois Urbana Champaign Authentication](https://apis.io/security/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-authentication/)
- [University Of Illinois Urbana Champaign Domain Security](https://apis.io/security/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [University Of Illinois Urbana Champaign Scopes](https://apis.io/scopes/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Illinois Urbana Champaign Plans Pricing](https://apis.io/plans/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Illinois Urbana Champaign Rate Limits](https://apis.io/rate-limits/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Illinois Urbana Champaign Finops](https://apis.io/finops/university-of-illinois-urbana-champaign/university-of-illinois-urbana-champaign-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://illinois.edu/)
- [Documentation](https://api.rokwire.illinois.edu/gateway/doc/ui/)
- [API reference](https://api.rokwire.illinois.edu/core/doc/ui/)
- [Support](https://help.uillinois.edu/)
- [Blog](https://news.illinois.edu/feed/)
- [Terms of service](https://publish.illinois.edu/experts-help/terms-of-use/)
- [Privacy policy](https://www.library.illinois.edu/geninfo/policies/p_policy/)
- [GitHub](https://github.com/rokwire)

## API Evangelist rating

**Kin Score 41.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 58.7 |
| Contract governance | 31.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 21.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | — |

**Regulatory alignment 42.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-illinois-urbana-champaign/](https://apis.io/providers/university-of-illinois-urbana-champaign/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Illinois Urbana-Champaign: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-illinois-urbana-champaign/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
