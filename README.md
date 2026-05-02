# OpenRouter (openrouter)

OpenRouter is an API platform that provides unified access to multiple AI language models through a single interface. OpenRouter acts as a "router" or gateway that lets developers and applications access dozens of different AI models from various providers through one standardized API, rather than having to integrate with each provider separately.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence, Gateway, Large Language Models, Router

## Timestamps

- **Created:** 2025-08-19
- **Modified:** 2026-04-28

## APIs

### OpenRouter
OpenRouter provides unified access to hundreds of AI models through a single API endpoint. It implements the OpenAI API specification for chat completions, allowing developers to use any model with the same request and response format. Better prices, better uptime, no subscription.

**Human URL:** [https://openrouter.ai/](https://openrouter.ai/)

**Base URL:** https://openrouter.ai/api/v1

#### Tags

- Artificial Intelligence, Gateway, Large Language Models, Router

#### Properties

- [Documentation](https://openrouter.ai/)
- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [OpenAPI (upstream JSON)](https://openrouter.ai/openapi.json)
- [OpenAPI (curated)](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/openapi/openrouter-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-schema/openrouter-chat-message-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openrouter/refs/heads/main/json-ld/openrouter-context.jsonld)

### OpenRouter Chat Completions API
The Chat Completions API is the primary endpoint for generating model responses. It supports text and image inputs, streaming via Server-Sent Events, tool and function calling, structured outputs, and provider routing across 400+ AI models from 60+ providers through a single standardized interface at `/api/v1/chat/completions`.

**Human URL:** [https://openrouter.ai/docs/api/reference/overview](https://openrouter.ai/docs/api/reference/overview)

#### Tags

- Chat, Completions, Large Language Models

#### Properties

- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [Documentation](https://openrouter.ai/docs/api/reference/parameters)
- [Documentation](https://openrouter.ai/docs/api/reference/streaming)
- [OpenAPI](https://openrouter.ai/openapi.json)

### OpenRouter Models API
The Models API allows developers to list and discover all available AI models and their properties, including pricing, context lengths, supported features, and provider information. Endpoints include listing all models and listing all endpoints for a specific model.

**Human URL:** [https://openrouter.ai/docs/api/api-reference/models/get-models](https://openrouter.ai/docs/api/api-reference/models/get-models)

#### Tags

- Discovery, Models

#### Properties

- [Documentation](https://openrouter.ai/docs/api/api-reference/models/get-models)
- [Documentation](https://openrouter.ai/docs/guides/overview/models)
- [OpenAPI](https://openrouter.ai/openapi.json)

### OpenRouter Generation API
The Generation API allows querying for generation statistics and historical usage data, including token counts, cost calculations, cached token tracking, and reasoning token counts for completed requests via the `/api/v1/generation` endpoint.

**Human URL:** [https://openrouter.ai/docs/api/reference/overview](https://openrouter.ai/docs/api/reference/overview)

#### Tags

- Generation, Stats, Usage

#### Properties

- [Documentation](https://openrouter.ai/docs/api/reference/overview)
- [OpenAPI](https://openrouter.ai/openapi.json)

### OpenRouter Keys Management API
The Keys Management API enables programmatic creation, rotation, and management of OpenRouter API keys. Common use cases include SaaS applications that automatically create unique keys for each customer, key rotation for security compliance, and usage monitoring with automatic key disabling when limits are exceeded.

**Human URL:** [https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys](https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys)

#### Tags

- API Keys, Management, Provisioning

#### Properties

- [Documentation](https://openrouter.ai/docs/guides/overview/auth/provisioning-api-keys)
- [Documentation](https://openrouter.ai/docs/guides/overview/auth/management-api-keys)
- [OpenAPI](https://openrouter.ai/openapi.json)

## Common Properties

- [Website](https://openrouter.ai/)
- [Models](https://openrouter.ai/models)
- [Status](https://status.openrouter.ai/)
- [GettingStarted](https://openrouter.ai/docs/quickstart)
- [FAQ](https://openrouter.ai/docs/faq)
- [Pricing](https://openrouter.ai/models?fmt=table)
- [PrivacyPolicy](https://openrouter.ai/privacy)
- [TermsOfService](https://openrouter.ai/terms)
- [Portal](https://openrouter.ai/docs)
- [API Reference](https://openrouter.ai/docs/api/reference/overview)
- [Authentication](https://openrouter.ai/docs/api/reference/authentication)
- [RateLimits](https://openrouter.ai/docs/api/reference/limits)
- [Errors](https://openrouter.ai/docs/api/reference/errors-and-debugging)
- [Streaming](https://openrouter.ai/docs/api/reference/streaming)
- [OpenAPI JSON](https://openrouter.ai/openapi.json)
- [OpenAPI YAML](https://openrouter.ai/openapi.yaml)
- [Support](https://openrouter.ai/support)
- [Blog](https://openrouter.ai/announcements)
- [Discord](https://discord.com/invite/openrouter)
- [GitHubOrganization](https://github.com/OpenRouterTeam)
- [TypeScript SDK](https://github.com/OpenRouterTeam/typescript-sdk)
- [Python SDK](https://github.com/OpenRouterTeam/python-sdk)
- [APIKeys](https://openrouter.ai/settings/keys)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
