# Colossyan (colossyan)

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
