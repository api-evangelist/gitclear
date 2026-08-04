# GitClear (gitclear)

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

GitClear provides code and commit analytics for engineering teams, centered on its Diff Delta metric (formerly Line Impact) that scores durable code change beyond raw lines. Its public REST API exposes repositories, commits/data audits, Diff Delta reports, and developer management so teams can pull research-backed productivity and AI-ROI metrics programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gitclear/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gitclear/refs/heads/main/apis.yml)

## Tags

- Code Analytics
- Commit Analytics
- Developer Productivity
- Diff Delta
- Engineering Metrics

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### GitClear Repositories API

List and queue repository imports, and connect repositories that GitClear analyzes for commit history and Diff Delta scoring.

- **Human URL:** [https://www.gitclear.com/api_reference](https://www.gitclear.com/api_reference)
- **Base URL:** `https://www.gitclear.com/api/v1`

#### Tags

- Repositories
- Imports
- Code

#### Properties

- [Documentation](https://www.gitclear.com/help/customer_rest_api)
- [API Reference](https://www.gitclear.com/api_reference)
- [OpenAPI](openapi/gitclear-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitclear.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitclear.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitClear Commits API

Audit the underlying commits, pull requests, and issues behind report numbers, and trace per-line version history across a repository's commit graph.

- **Human URL:** [https://www.gitclear.com/api_reference](https://www.gitclear.com/api_reference)
- **Base URL:** `https://www.gitclear.com/api/v1`

#### Tags

- Commits
- Data Audit
- Line History

#### Properties

- [Documentation](https://www.gitclear.com/help/customer_rest_api)
- [API Reference](https://www.gitclear.com/api_reference)
- [OpenAPI](openapi/gitclear-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitclear.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitclear.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitClear Metrics & Diff Delta API

Fetch chart and report data across 160+ measured segments - Diff Delta, PR comments, releases - aggregated and segmented by repo, team, issue type, and code domain over time.

- **Human URL:** [https://www.gitclear.com/api_reference](https://www.gitclear.com/api_reference)
- **Base URL:** `https://www.gitclear.com/api/v1`

#### Tags

- Metrics
- Diff Delta
- Reports

#### Properties

- [Documentation](https://www.gitclear.com/diff_delta_factors)
- [API Reference](https://www.gitclear.com/api_reference)
- [OpenAPI](openapi/gitclear-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitclear.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitclear.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GitClear Developers API

List developers and their activity, record and remove time off, set per-developer stat processing status, and create or update teams programmatically.

- **Human URL:** [https://www.gitclear.com/api_reference](https://www.gitclear.com/api_reference)
- **Base URL:** `https://www.gitclear.com/api/v1`

#### Tags

- Developers
- Teams
- Activity

#### Properties

- [Documentation](https://www.gitclear.com/help/customer_rest_api)
- [API Reference](https://www.gitclear.com/api_reference)
- [OpenAPI](openapi/gitclear-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gitclear.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gitclear.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/gitclear)
- [LinkedIn](https://www.linkedin.com/company/gitclear)
- [Website](https://www.gitclear.com)
- [Documentation](https://www.gitclear.com/api_reference)
- [Plans](plans/gitclear-plans-pricing.yml)
- [Rate Limits](rate-limits/gitclear-rate-limits.yml)
- [Fin Ops](finops/gitclear-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
