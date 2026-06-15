# OpenRouter (openrouter)

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
