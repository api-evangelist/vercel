# Vercel

Vercel is a cloud platform for frontend developers that makes it easy to build, deploy, and scale modern web applications. It provides optimized hosting for Next.js (which it created), React, Vue, Angular, and static site projects with automatic CI/CD, edge caching, and serverless functions. Beyond deployment, Vercel offers an AI Gateway for unified access to hundreds of LLMs, and v0 for AI-powered application generation.

**URL:** [https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI Gateways, Gateways, Observability, Deployments, Serverless, Next.js

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-03

## APIs

### Vercel REST API

The Vercel REST API provides programmatic access to deployments, domains, projects, teams, DNS, certificates, edge config, environment variables, and more. All endpoints live under `https://api.vercel.com`. An official OpenAPI spec is published at [openapi.vercel.sh](https://openapi.vercel.sh/).

**Human URL:** [https://vercel.com/docs/rest-api/reference](https://vercel.com/docs/rest-api/reference)

**Tags:** Access Groups, Billing, Certificates, Deployments, DNS, Domains, Edge Config, Environment Variables, Projects, Teams, Webhooks

#### Properties

- [Documentation](https://vercel.com/docs/rest-api/reference)
- [OpenAPI](https://openapi.vercel.sh/)
- [Rate Limits](https://vercel.com/docs/rest-api/reference#rate-limits)
- [Pagination](https://vercel.com/docs/rest-api/reference#pagination)
- [Versioning](https://vercel.com/docs/rest-api/reference#versioning)

### Vercel AI Gateway API

Unified OpenAI-compatible API to access hundreds of AI models from Anthropic, OpenAI, Google, Meta, Mistral and more through a single endpoint at `https://ai-gateway.vercel.sh/v1`. Features provider routing by cost/latency/throughput, automatic fallbacks, and zero markup pricing.

**Human URL:** [https://vercel.com/docs/ai-gateway](https://vercel.com/docs/ai-gateway)

**Tags:** AI, AI Gateway, LLM, Machine Learning, Models

#### Properties

- [Documentation](https://vercel.com/docs/ai-gateway)
- [OpenAPI](openapi/vercel-ai-gateway-openapi.yml)
- [Getting Started](https://vercel.com/docs/ai-gateway/getting-started)

### V0 Platform API

The v0 Platform API provides programmatic access to v0's AI-powered app generation pipeline. Generate full-stack Next.js web applications from natural language prompts. Requires Premium or Team plan.

**Human URL:** [https://v0.dev/docs](https://v0.dev/docs)

**Tags:** AI, App Builder, Code Generation

#### Properties

- [Documentation](https://v0.dev/docs)
- [OpenAPI](openapi/vercel-v0-platform-openapi.yml)
- [GitHub - v0 SDK](https://github.com/vercel/v0-sdk)

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/vercel-ai-gateway.yaml](capabilities/shared/vercel-ai-gateway.yaml) | AI Gateway — models, chat completions, embeddings (3 operations) |
| [capabilities/shared/vercel-v0-platform.yaml](capabilities/shared/vercel-v0-platform.yaml) | v0 Platform API — app generation, iteration, retrieval (3 operations) |

### Workflow Capabilities

| Capability | APIs | MCP Tools |
|---|---|---|
| [ai-development](capabilities/ai-development.yaml) | AI Gateway + v0 Platform | 6 tools |

## Artifacts

| Type | Files |
|---|---|
| OpenAPI | [openapi/vercel-ai-gateway-openapi.yml](openapi/vercel-ai-gateway-openapi.yml), [openapi/vercel-v0-platform-openapi.yml](openapi/vercel-v0-platform-openapi.yml) |
| JSON Schema | [json-schema/vercel-chat-completion-schema.json](json-schema/vercel-chat-completion-schema.json) |
| JSON Structure | [json-structure/vercel-chat-completion-structure.json](json-structure/vercel-chat-completion-structure.json) |
| JSON-LD | [json-ld/vercel-context.jsonld](json-ld/vercel-context.jsonld) |
| Examples | [examples/](examples/) (3 examples) |
| Spectral Rules | [rules/vercel-rules.yml](rules/vercel-rules.yml) |
| Vocabulary | [vocabulary/vercel-vocabulary.yml](vocabulary/vercel-vocabulary.yml) |

## Common Properties

- [Website](https://vercel.com/)
- [Documentation](https://vercel.com/docs)
- [Changelog](https://vercel.com/changelog)
- [Blog](https://vercel.com/blog)
- [Marketplace / Integrations](https://vercel.com/marketplace)
- [Pricing](https://vercel.com/pricing)
- [Templates](https://vercel.com/templates)
- [GitHub Organization](https://github.com/vercel/vercel)
- [Community Forum](https://community.vercel.com/)
- [Status Page](https://www.vercel-status.com)
- [Support](https://vercel.com/help)
- [Trust Center / Security](https://security.vercel.com)
- [Terms of Service](https://vercel.com/legal/terms)
- [Privacy Policy](https://vercel.com/legal/privacy-policy)
- [CLI](https://vercel.com/docs/cli)
- [AI SDK](https://vercel.com/docs/ai-sdk)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
