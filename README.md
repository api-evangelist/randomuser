# Random User Generator (randomuser)

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

Free, open-source REST API that generates rich, realistic synthetic user records (name, location, login, contact, picture, identification, nationality) for application testing, prototyping, and demo content. Powered by the open-source Randomuser.me-Node project under the MIT license and funded by community donations. Single unauthenticated GET endpoint, seedable for reproducibility, with multi-format output (JSON, PrettyJSON, CSV, YAML, XML).

**APIs.json:** [https://randomuser.me](https://randomuser.me)

## Tags

- Test Data
- Synthetic Data
- Mock Data
- Open Source
- Public API
- Free API

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Random User Generator API

Single GET endpoint that returns a configurable batch of synthetic users. Supports up to 5000 results per request, multi-nationality mixing, field include/exclude projection, deterministic seeds with pagination, multiple serialization formats, and path-pinned versioning (1.0 - 1.4).

- **Human URL:** [https://randomuser.me](https://randomuser.me)
- **Base URL:** `https://randomuser.me/api`

#### Tags

- Test Data
- Synthetic Data

#### Properties

- [Documentation](https://randomuser.me/documentation)
- [API Reference](https://randomuser.me/documentation)
- [OpenAPI](openapi/randomuser-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/randomuser.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/randomuser.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/randomuser-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/randomuser-user-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/randomuser-user-structure.json)
- [JSON-LD](json-ld/randomuser-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/randomuser-generate-users-example.json)
- [Example](examples/randomuser-paginated-seed-example.json)
- [Example](examples/randomuser-csv-export-example.json)
- [Rate Limits](rate-limits/randomuser-rate-limits.yml)
- [Plans](plans/randomuser-plans-pricing.yml)
- [Authentication](https://randomuser.me/documentation)
- [Versioning](https://randomuser.me/documentation#versioning)
- [Changelog](https://randomuser.me/changelog)

## Common Properties

- [Website](https://randomuser.me)
- [Documentation](https://randomuser.me/documentation)
- [Changelog](https://randomuser.me/changelog)
- [GitHub Organization](https://github.com/RandomAPI)
- [GitHub Repository](https://github.com/RandomAPI/Randomuser.me-Node)
- [GitHub Repository](https://github.com/RandomAPI/Offline-RandomAPI)
- [GitHub Repository](https://github.com/RandomAPI/Randomuser.me-module)
- [X (Twitter)](https://twitter.com/randomapi)
- [Pricing](https://randomuser.me/#donate)
- [Support](https://github.com/RandomAPI/Randomuser.me-Node/issues)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/randomuser-rules.yml)
- [Vocabulary](vocabulary/randomuser-vocabulary.yml)
- [Tools](https://github.com/pipeworx-io/mcp-randomuser)
- [Tools](https://github.com/hugo-85/mcp-randomuserme)
- [Tools](https://github.com/rycid/randomuserMCP)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
