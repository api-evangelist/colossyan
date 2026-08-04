# Colossyan (colossyan)

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

Colossyan is an AI avatar and video generation platform for learning and development. Its REST API turns scripts into studio-quality videos with AI avatars and voices, lists avatars/presenters, voices and templates, supports instant avatar and voice clone creation, and exposes asynchronous video-generation jobs with webhook callbacks. API access requires a Business or Enterprise plan.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/colossyan/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/colossyan/refs/heads/main/apis.yml)

## Tags

- AI
- Video Generation
- Avatars
- Text to Video
- Learning and Development

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Colossyan Video Generation API

Creates videos from a script + avatar + voice by submitting an asynchronous video-generation job, with template-based generation, dynamic variable substitution, and retrieval/deletion of generated videos.

- **Human URL:** [https://docs.colossyan.com/basics/video-generation](https://docs.colossyan.com/basics/video-generation)
- **Base URL:** `https://app.colossyan.com/api/v1`

#### Tags

- Video Generation
- Text to Video
- Async

#### Properties

- [Documentation](https://docs.colossyan.com/basics/video-generation)
- [API Reference](https://docs.colossyan.com/)
- [OpenAPI](openapi/colossyan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colossyan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colossyan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Colossyan Avatars / Presenters API

Lists available avatars/presenters (Studio, Scenario, and Instant types) and creates custom Instant avatars from a source image or video URL.

- **Human URL:** [https://docs.colossyan.com/avatar-creation/create-avatar](https://docs.colossyan.com/avatar-creation/create-avatar)
- **Base URL:** `https://app.colossyan.com/api/v1`

#### Tags

- Avatars
- Presenters
- Instant Avatar

#### Properties

- [Documentation](https://docs.colossyan.com/avatar-creation/create-avatar)
- [API Reference](https://docs.colossyan.com/basics/openapi/list-avatars)
- [OpenAPI](openapi/colossyan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colossyan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colossyan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Colossyan Voices API

Lists the AI voices available for narration across the platform's supported languages, identified by a speaker ID used in video generation.

- **Human URL:** [https://docs.colossyan.com/](https://docs.colossyan.com/)
- **Base URL:** `https://app.colossyan.com/api/v1`

#### Tags

- Voices
- Text to Speech
- Languages

#### Properties

- [Documentation](https://docs.colossyan.com/)
- [OpenAPI](openapi/colossyan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colossyan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colossyan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Colossyan Templates API

Generates videos from reusable Colossyan templates, supplying dynamic variables to populate text, avatars, and media placeholders.

- **Human URL:** [https://docs.colossyan.com/basics/video-generation](https://docs.colossyan.com/basics/video-generation)
- **Base URL:** `https://app.colossyan.com/api/v1`

#### Tags

- Templates
- Video Generation

#### Properties

- [Documentation](https://docs.colossyan.com/basics/video-generation)
- [OpenAPI](openapi/colossyan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colossyan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colossyan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Colossyan Job Status / Webhooks API

Retrieves and cancels video-generation jobs and delivers completion notifications to a caller-supplied callback (webhook) URL with the public video URL, status, and custom callback payload.

- **Human URL:** [https://docs.colossyan.com/basics/video-generation](https://docs.colossyan.com/basics/video-generation)
- **Base URL:** `https://app.colossyan.com/api/v1`

#### Tags

- Job Status
- Webhooks
- Callbacks

#### Properties

- [Documentation](https://docs.colossyan.com/basics/video-generation)
- [OpenAPI](openapi/colossyan-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/colossyan.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/colossyan.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/colossyan)
- [LinkedIn](https://www.linkedin.com/company/colossyan)
- [Website](https://www.colossyan.com)
- [Documentation](https://docs.colossyan.com)
- [Plans](plans/colossyan-plans-pricing.yml)
- [Rate Limits](rate-limits/colossyan-rate-limits.yml)
- [Fin Ops](finops/colossyan-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
