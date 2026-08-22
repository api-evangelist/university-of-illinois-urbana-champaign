# University of Illinois Urbana-Champaign (university-of-illinois-urbana-champaign)

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

The University of Illinois Urbana-Champaign (UIUC) is the public land-grant flagship of the University of Illinois System and a founding Big Ten institution. This repository catalogs UIUC's public developer and API footprint as an [APIs.json](https://apisjson.org) profile.

UIUC is one of the few universities in this cohort that genuinely **engineers** a public API estate rather than buying one. Every surface below carries an `x-operator` in `apis.yml`: `institution` where UIUC runs the thing the contract describes, `tenant` where the data is UIUC's but the contract belongs to a vendor. No vendor specification is saved under this institution.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-illinois-urbana-champaign/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-illinois-urbana-champaign-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Public Research University, United States, Illinois, Big Ten, Land-Grant University, Course Catalog, Research Data, Research Repository, Open Data, Identity Federation, OAI-PMH, Library, Research Computing, Open Source

## APIs

### Institution-operated (`x-operator: institution`)

- **Rokwire Core Building Block API** — identity, accounts, applications, organizations, service registrations, permissions/roles/scopes. UIUC-written, Apache 2.0, v1.62.0, 105 paths / 151 operations. `https://api.rokwire.illinois.edu/core` · [Swagger UI](https://api.rokwire.illinois.edu/core/doc/ui/) · [source](https://github.com/rokwire/core-building-block)
- **Rokwire Gateway Building Block API** — wayfinding, buildings/floorplans, campus data streams, third-party integration. v2.21.1, 34 paths / 45 operations. `https://api.rokwire.illinois.edu/gateway` · [Swagger UI](https://api.rokwire.illinois.edu/gateway/doc/ui/) · [source](https://github.com/rokwire/gateway-building-block)
- **Course Explorer (CISAPI)** — Class Schedule and Course Catalog XML, no authentication. [Docs](https://courses.illinois.edu/cisdocs/api)
- **IDEALS OAI-PMH** — OAI-PMH 2.0 data provider, four metadata formats (oai_dc, qdc, etdms, native), 100 sets. Runs on Illinois Library's own Rails application, not a vendor repository platform. `https://www.ideals.illinois.edu/oai-pmh`
- **Illinois Data Bank** — in-house research data repository; `/datasets.json` returns all 1,259 released datasets without authentication. Registered DataCite repository `illinois.databank`, 1,306 DOIs under prefix 10.13012, 1,082 carrying ORCID creator identifiers. `https://databank.illinois.edu`
- **Shibboleth Identity Provider (InCommon)** — SAML 1.1/2.0 IdP metadata, entityID `urn:mace:incommon:uiuc.edu`, also resolvable through the InCommon metadata query service. `https://shibboleth.illinois.edu/idp/shibboleth`

### Tenant relationships (`x-operator: tenant` — the data is UIUC's, the contract is the vendor's)

- **Illinois Experts** — Elsevier Pure / Pure Portal. Recorded as a relationship; the Pure API contract belongs in Elsevier's repo.
- **University Library Discovery** — Ex Libris Primo VE; `search.library.illinois.edu` redirects into `primo.exlibrisgroup.com/discovery`.

### Live but not yet contracted

Seven further Rokwire building blocks answer an unauthenticated `/version` on the production host and ship no contract in this repo: calendar 1.98.0, social 1.61.0, notifications 1.28.0, appointments 1.27.2, content 1.14.3, surveys 1.14.1, polls 1.12.1. See [lifecycle/](lifecycle/university-of-illinois-urbana-champaign-lifecycle.yml).

### Standards conformance

Verified against the Kin Score `education` regime: **oai-pmh**, **shibboleth**, **saml**, **datacite** and **orcid** all conform with probed evidence; scim, lti, oneroster, ed-fi, caliper, qti and crossref do not. Full evidence in [conformance/](conformance/university-of-illinois-urbana-champaign-conformance.yml).

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-illinois-urbana-champaign-plans-pricing.yml](plans/university-of-illinois-urbana-champaign-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-illinois-urbana-champaign-rate-limits.yml](rate-limits/university-of-illinois-urbana-champaign-rate-limits.yml)
- FinOps: [finops/university-of-illinois-urbana-champaign-finops.yml](finops/university-of-illinois-urbana-champaign-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://illinois.edu/
- GitHub (Rokwire platform): https://github.com/rokwire
- SourceCode (Illinois org): https://github.com/illinois
- LinkedIn: https://www.linkedin.com/school/university-of-illinois-at-urbana-champaign/
- Status: https://status.illinois.edu/

## Notes

All cataloged endpoints were verified live on 2026-06-03. The Course Explorer schedule and catalog endpoints return XML with no authentication. The Rokwire Core and Gateway Swagger UIs and the IDEALS OAI-PMH endpoint all responded HTTP 200. The `api.rokwire.illinois.edu/docs/` path referenced in some sources returns 404 and was deliberately not cataloged. The LinkedIn school page returns HTTP 999 due to anti-bot protection but is the canonical URL. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
