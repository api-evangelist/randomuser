# Random User Generator (randomuser)

Free, open-source REST API that generates rich, realistic synthetic user records (name, location, login, contact, picture, identification, nationality) for application testing, prototyping, and demo content. Powered by the open-source Randomuser.me-Node project under the MIT license and funded by community donations. Single unauthenticated GET endpoint, seedable for reproducibility, with multi-format output (JSON, PrettyJSON, CSV, YAML, XML).

**URL:** [Visit APIs.json URL](https://randomuser.me)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Test Data, Synthetic Data, Mock Data, Open Source, Public API, Free API

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Type

- **x-type:** opensource
- **x-tier:** 2 (enriched via full pipeline)
- **License:** MIT
- **Canonical source:** [RandomAPI/Randomuser.me-Node](https://github.com/RandomAPI/Randomuser.me-Node)

## APIs

### Random User Generator API

Single GET endpoint that returns a configurable batch of synthetic users. Supports up to 5000 results per request, multi-nationality mixing, field include/exclude projection, deterministic seeds with pagination, multiple serialization formats, and path-pinned versioning (1.0 - 1.4).

**Human URL:** [https://randomuser.me](https://randomuser.me)

**Base URL:** `https://randomuser.me/api`

#### Tags

- Test Data, Synthetic Data

#### Properties

- [Documentation](https://randomuser.me/documentation)
- [APIReference](https://randomuser.me/documentation)
- [OpenAPI](openapi/randomuser-openapi.yml)
- [JSONSchema - User Schema](json-schema/randomuser-user-schema.json)
- [JSONSchema - User Response Schema](json-schema/randomuser-user-response-schema.json)
- [JSONStructure](json-structure/randomuser-user-structure.json)
- [JSONLD](json-ld/randomuser-context.jsonld)
- [Example - Generate Users](examples/randomuser-generate-users-example.json)
- [Example - Paginated Seeded Request](examples/randomuser-paginated-seed-example.json)
- [Example - CSV Export with Download Flag](examples/randomuser-csv-export-example.json)
- [RateLimits](rate-limits/randomuser-rate-limits.yml)
- [Plans](plans/randomuser-plans-pricing.yml)
- [Authentication - None (Public, Unauthenticated)](https://randomuser.me/documentation)
- [Versioning](https://randomuser.me/documentation#versioning)
- [ChangeLog](https://randomuser.me/changelog)

## Common Properties

- [Website](https://randomuser.me)
- [Documentation](https://randomuser.me/documentation)
- [ChangeLog](https://randomuser.me/changelog)
- [GitHubOrganization](https://github.com/RandomAPI)
- [GitHubRepository - Randomuser.me-Node (Canonical Source)](https://github.com/RandomAPI/Randomuser.me-Node)
- [GitHubRepository - Offline RandomAPI npm module](https://github.com/RandomAPI/Offline-RandomAPI)
- [GitHubRepository - Offline User Generation Module](https://github.com/RandomAPI/Randomuser.me-module)
- [X](https://twitter.com/randomapi)
- [Pricing - Free (Donation-Funded)](https://randomuser.me/#donate)
- [Support](https://github.com/RandomAPI/Randomuser.me-Node/issues)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [SpectralRules](rules/randomuser-rules.yml)
- [Vocabulary](vocabulary/randomuser-vocabulary.yml)
- [NaftikoCapability - RandomUser Users (Shared)](capabilities/shared/randomuser-users.yaml)
- [NaftikoCapability - Generate Deterministic Test Fixtures](capabilities/seed-test-fixtures.yaml)
- [NaftikoCapability - Build a Multi-Nationality User Cohort](capabilities/multi-nationality-cohort.yaml)
- [Tools - MCP Server (pipeworx-io)](https://github.com/pipeworx-io/mcp-randomuser)
- [Tools - MCP Server (hugo-85)](https://github.com/hugo-85/mcp-randomuserme)
- [Tools - MCP Server (rycid)](https://github.com/rycid/randomuserMCP)

## Features

| Name | Description |
|------|-------------|
| Free and unauthenticated | No API key, no signup, no per-key quotas; just hit the endpoint. |
| Seedable reproducibility | The same (seed, page, results, version) tuple always returns the same users. |
| Multi-nationality cohort | Mix 21 nationalities (v1.4) so addresses, IDs, and phone formats stay locale-appropriate. |
| Field projection | Use `inc` / `exc` to keep payloads small and skip CPU-heavy fields like `login`. |
| Multi-format output | JSON, PrettyJSON, CSV, YAML, XML; plus JSONP via `callback`. |
| Path-pinned versioning | Lock requests to /1.0/ through /1.4/ so upstream releases never break your fixtures. |
| Pre-generated portrait images | Three resolutions (large, medium, thumbnail) hosted on randomuser.me. |
| Open source | MIT-licensed Node.js codebase; self-hostable if you need air-gapped operation. |

## Use Cases

| Name | Description |
|------|-------------|
| Frontend prototyping | Populate UI mockups, design comps, and Storybook fixtures with realistic users. |
| Test data for QA / CI | Generate seeded fixtures for unit, integration, and snapshot tests. |
| Load testing | Bulk-generate up to 5000 users per request to seed performance test runs. |
| i18n / localization | Request specific nationalities to validate address parsing, phone formats, and Unicode rendering. |
| Demo content | Populate sales demos, sandbox environments, and tutorials with realistic-looking accounts. |
| Avatar placeholders | Use the picture URLs as throwaway avatars for prototyping. |

## Integrations

| Name | Description |
|------|-------------|
| jQuery / AJAX | Documented usage with $.ajax for browser-side fetches. |
| Node.js | Use directly from server-side JavaScript; offline module available. |
| Photoshop Extension | Pull synthetic users straight into design comps (legacy extension). |
| Sketch Extension | Sketch plugin for filling layers with random users (legacy). |
| Model Context Protocol | Multiple community MCP servers expose the API to LLM agents (pipeworx-io, hugo-85, rycid). |

## Solutions

| Name | Description |
|------|-------------|
| Hosted API | Free, public, donation-funded endpoint at randomuser.me/api. |
| Offline npm module | Generate the same shape of users without network calls using the offline RandomAPI module. |
| Self-hosted | Clone Randomuser.me-Node and run the generator inside your own infrastructure. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Random User Generator API](openapi/randomuser-openapi.yml)

### JSON Schema

- [User](json-schema/randomuser-user-schema.json)
- [User Response](json-schema/randomuser-user-response-schema.json)

### JSON Structure

- [User Structure](json-structure/randomuser-user-structure.json)

### JSON-LD

- [RandomUser Context](json-ld/randomuser-context.jsonld)

### Examples

- [Generate Users](examples/randomuser-generate-users-example.json)
- [Paginated Seeded Request](examples/randomuser-paginated-seed-example.json)
- [CSV Export with Download Flag](examples/randomuser-csv-export-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [RandomUser Users](capabilities/shared/randomuser-users.yaml) - 2 operations for synthetic user generation

### Workflow Capabilities

| Workflow | APIs Combined | Persona |
|----------|---------------|---------|
| [Generate Deterministic Test Fixtures](capabilities/seed-test-fixtures.yaml) | randomuser | QA / Test Engineering |
| [Build a Multi-Nationality User Cohort](capabilities/multi-nationality-cohort.yaml) | randomuser | i18n / Localization Engineering |

## Vocabulary

- [RandomUser Vocabulary](vocabulary/randomuser-vocabulary.yml) - Controlled vocabulary covering 2 operations, 3 entities, 12 request parameters, and 21 supported nationalities (v1.4) across the operational dimension.

## Rules

- [RandomUser Spectral Rules](rules/randomuser-rules.yml) - 10 rules enforcing operationId casing, Title Case summaries, tag presence, parameter enumerations, results cap, no-auth posture, HTTPS servers, User schema presence, and Microcks mocking metadata.

## Plans & Rate Limits

- [Plans](plans/randomuser-plans-pricing.yml) - Free, donation-funded, no commercial tier.
- [Rate Limits](rate-limits/randomuser-rate-limits.yml) - No documented per-key or per-IP rate cap; hard 5000 results per request.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
