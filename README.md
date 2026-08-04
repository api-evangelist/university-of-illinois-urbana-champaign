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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Illinois Urbana-Champaign (UIUC) is a public land-grant research university and the flagship campus of the University of Illinois System, ranked #40 in the QS World University Rankings 2025. This repository catalogs UIUC's public developer and API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-illinois-urbana-champaign/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-illinois-urbana-champaign-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Courses, Library, United States

## APIs

- **Course Explorer (CISAPI)** — RESTful Class Schedule and Course Catalog data (Schedule, Catalog, GenEd, Term, Subjects modules); public, no authentication. Docs: https://courses.illinois.edu/cisdocs/api
- **Rokwire Core Building Block** — Users, accounts, profiles, organizations, and authentication for the open-source Illinois app platform. Docs: https://api.rokwire.illinois.edu/core/doc/ui/
- **Rokwire Gateway Building Block** — Access to external university systems and data streams. Docs: https://api.rokwire.illinois.edu/gateway/doc/ui/
- **IDEALS OAI-PMH** — Institutional repository metadata harvesting endpoint. Docs: https://guides.library.illinois.edu/ideals

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
