# OpenRouter (openrouter)

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

OpenRouter is an API platform that provides unified access to multiple AI language models through a single interface. OpenRouter acts as a "router" or gateway that lets developers and applications access dozens of different AI models from various providers through one standardized API, rather than having to integrate with each provider separately.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Gateway
- Large Language Models
- Router

## Timestamps

- **Created:** 2025-08-19T00:00:00.000Z
- **Modified:** 2026-05-19

## APIs

### OpenRouter

OpenRouter provides unified access to hundreds of AI models through a single API endpoint. It implements the OpenAI API specification for chat completions, allowing developers to use any model with the same request and response format. Better prices, better uptime, no subscription.

- **Human URL:** [https://openrouter.ai/](https://openrouter.ai/)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- Artificial Intelligence
- Gateway
- Large Language Models
- Router

#### Properties

- [Documentation](https://openrouter.ai/)
- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/openapi/openrouter-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-schema/openrouter-chat-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-ld/openrouter-context.jsonld)
- [Postman Collection](collections/openrouter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openrouter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenRouter Chat Completions API

The Chat Completions API is the primary endpoint for generating model responses. It supports text and image inputs, streaming via Server-Sent Events, tool and function calling, structured outputs, and provider routing across 400+ AI models from 60+ providers through a single standardized interface at /api/v1/chat/completions.

- **Human URL:** [https://openrouter.ai/docs/api/reference/overview](https://openrouter.ai/docs/api/reference/overview)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- Chat
- Completions
- Large Language Models

#### Properties

- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [Documentation](https://openrouter.ai/docs/api/reference/parameters)
- [Documentation](https://openrouter.ai/docs/api/reference/streaming)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openrouter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openrouter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenRouter Models API

The Models API allows developers to list and discover all available AI models and their properties, including pricing, context lengths, supported features, and provider information. Endpoints include listing all models and listing all endpoints for a specific model.

- **Human URL:** [https://openrouter.ai/docs/api/api-reference/models/get-models](https://openrouter.ai/docs/api/api-reference/models/get-models)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- Discovery
- Models

#### Properties

- [Documentation](https://openrouter.ai/docs/api/api-reference/models/get-models)
- [Documentation](https://openrouter.ai/docs/guides/overview/models)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openrouter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openrouter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenRouter Generation API

The Generation API allows querying for generation statistics and historical usage data, including token counts, cost calculations, cached token tracking, and reasoning token counts for completed requests via the /api/v1/generation endpoint.

- **Human URL:** [https://openrouter.ai/docs/api/reference/overview](https://openrouter.ai/docs/api/reference/overview)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- Generation
- Stats
- Usage

#### Properties

- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openrouter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openrouter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenRouter Keys Management API

The Keys Management API enables programmatic creation, rotation, and management of OpenRouter API keys. Common use cases include SaaS applications that automatically create unique keys for each customer, key rotation for security compliance, and usage monitoring with automatic key disabling when limits are exceeded.

- **Human URL:** [https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys](https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys)
- **Base URL:** `https://openrouter.ai/api/v1`

#### Tags

- API Keys
- Management
- Provisioning

#### Properties

- [Documentation](https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys)
- [Documentation](https://openrouter.ai/docs/guides/overview/auth/management-api-keys)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openrouter.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openrouter.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/openrouter)
- [Website](https://openrouter.ai/)
- [Models](https://openrouter.ai/models)
- [Status Page](https://status.openrouter.ai/)
- [Getting Started](https://openrouter.ai/docs/quickstart)
- [F A Q](https://openrouter.ai/docs/faq)
- [Pricing](https://openrouter.ai/models?fmt=table)
- [Privacy Policy](https://openrouter.ai/privacy)
- [Terms of Service](https://openrouter.ai/terms)
- [Portal](https://openrouter.ai/docs)
- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [Authentication](https://openrouter.ai/docs/api/reference/authentication)
- [Rate Limits](https://openrouter.ai/docs/api/reference/limits)
- [Errors](https://openrouter.ai/docs/api/reference/errors-and-debugging)
- [Documentation](https://openrouter.ai/docs/api/reference/streaming)
- [OpenAPI](https://openrouter.ai/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://openrouter.ai/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://openrouter.ai/pricing)
- [Support](https://openrouter.ai/support)
- [Blog](https://openrouter.ai/announcements)
- [Discord](https://discord.com/invite/openrouter)
- [GitHub Organization](https://github.com/OpenRouterTeam)
- [GitHub Repository](https://github.com/OpenRouterTeam/typescript-sdk)
- [GitHub Repository](https://github.com/OpenRouterTeam/python-sdk)
- [S D Ks](https://openrouter.ai/docs/sdks/typescript/overview)
- [S D Ks](https://openrouter.ai/docs/sdks/python/overview)
- [Integrations](https://openrouter.ai/docs/guides/community/frameworks-and-integrations-overview)
- [Documentation](https://openrouter.ai/docs/guides/community/openai-sdk)
- [Documentation](https://openrouter.ai/docs/guides/routing/provider-selection)
- [Documentation](https://openrouter.ai/docs/guides/features/tool-calling)
- [Documentation](https://openrouter.ai/docs/guides/features/structured-outputs)
- [Documentation](https://openrouter.ai/docs/guides/features/model-routing)
- [Documentation](https://openrouter.ai/docs/guides/features/guardrails)
- [Documentation](https://openrouter.ai/docs/guides/features/zdr)
- [Documentation](https://openrouter.ai/docs/guides/features/plugins/web-search)
- [Documentation](https://openrouter.ai/docs/guides/overview/auth/byok)
- [Documentation](https://openrouter.ai/docs/guides/guides/for-providers)
- [A P I Keys](https://openrouter.ai/settings/keys)
- [Documentation](https://openrouter.ai/docs/guides/overview/principles)
- [Features](undefined)
- [L L Ms Txt](https://openrouter.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
