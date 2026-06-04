# University of Illinois Urbana-Champaign (university-of-illinois-urbana-champaign)

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
