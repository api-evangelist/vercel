# Vercel (vercel)

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

Vercel is a cloud platform that helps developers build, deploy, and scale modern web applications quickly and efficiently. It provides an optimized hosting environment for frontend frameworks like Next.js (which it created), as well as other React, Vue, Angular, and static site projects. Vercel automates workflows for continuous deployment, edge caching, and serverless functions, so developers can push code changes and see them live almost instantly.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI Gateways
- Gateways
- Observability
- Webhooks

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-30

## APIs

### Vercel

Vercel is a developer cloud to build and deploy web applications.

- **Human URL:** [ https://vercel.com/docs]( https://vercel.com/docs)

#### Properties

- [Documentation]( https://vercel.com/docs)
- [Postman Collection](collections/vercel-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vercel-v0-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-v0-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vercel REST API

The Vercel REST API provides programmatic access to the Vercel platform. All endpoints live under https://api.vercel.com and follow REST architecture over SSL. The API covers deployments, domains, projects, teams, DNS, certificates, edge config, environment variables, access groups, billing, security, webhooks, and more. Authentication uses Bearer tokens via the Authorization header.

- **Human URL:** [https://vercel.com/docs/rest-api/reference](https://vercel.com/docs/rest-api/reference)

#### Tags

- Access Groups
- Billing
- Certificates
- Deployments
- DNS
- Domains
- Edge Config
- Environment Variables
- Projects
- Teams
- Webhooks

#### Properties

- [Documentation](https://vercel.com/docs/rest-api/reference)
- [OpenAPI](https://openapi.vercel.sh/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rate Limits](https://vercel.com/docs/rest-api/reference#rate-limits)
- [Pagination](https://vercel.com/docs/rest-api/reference#pagination)
- [Versioning](https://vercel.com/docs/rest-api/reference#versioning)
- [Postman Collection](collections/vercel-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vercel-v0-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-v0-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vercel AI Gateway API

The Vercel AI Gateway provides a unified API to access hundreds of AI models from multiple providers through a single endpoint at https://ai-gateway.vercel.sh/v1. It offers one key for hundreds of models, spend monitoring, automatic retries and fallbacks, embeddings support, and zero markup on token pricing. Compatible with the AI SDK, OpenAI SDK, and Anthropic SDK.

- **Human URL:** [https://vercel.com/docs/ai-gateway](https://vercel.com/docs/ai-gateway)

#### Tags

- AI
- AI Gateway
- LLM
- Machine Learning
- Models

#### Properties

- [Documentation](https://vercel.com/docs/ai-gateway)
- [Getting Started](https://vercel.com/docs/ai-gateway/getting-started)
- [Documentation](https://vercel.com/docs/ai-gateway/models-and-providers)
- [Documentation](https://vercel.com/docs/ai-gateway/sdks-and-apis/openai-compat)
- [Usage Billing](https://vercel.com/docs/ai-gateway/usage)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-ai-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vercel-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vercel-v0-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-v0-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vercel Webhooks

Vercel Webhooks deliver platform events to a subscriber-configured HTTPS endpoint via HTTP POST with a JSON body. Subscriptions are created as Account Webhooks (Team Settings) or through Vercel Integrations and can opt in to deployment, project, project domain, project environment variable, project rolling release, domain, feature flag, integration configuration, integration resource, marketplace invoice, marketplace member, and observability alert events. Every delivery shares a common envelope (id, type, createdAt, region, payload) and is signed with HMAC-SHA1 using the webhook secret, sent in the x-vercel-signature header.

- **Human URL:** [https://vercel.com/docs/webhooks](https://vercel.com/docs/webhooks)

#### Tags

- Webhooks
- Deployments
- Projects
- Domains
- Integrations
- Marketplace
- Events

#### Properties

- [Documentation](https://vercel.com/docs/webhooks)
- [API Reference](https://vercel.com/docs/webhooks/webhooks-api)
- [Security](https://vercel.com/docs/headers/request-headers#x-vercel-signature)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/asyncapi/vercel-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/vercel-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vercel-v0-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-v0-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### V0 Platform API

The v0 Platform API provides programmatic access to v0's AI-powered app generation pipeline. It is a REST interface that wraps v0's full code generation lifecycle from prompt to project to code files to deployment. Capabilities include generating full-stack web apps from natural language prompts, structured parsing of generated code, automatic error fixing, and linking with rendered previews. A TypeScript SDK is available.

- **Human URL:** [https://v0.dev/docs](https://v0.dev/docs)

#### Tags

- AI
- App Builder
- Code Generation

#### Properties

- [Documentation](https://v0.dev/docs)
- [GitHub Organization](https://github.com/vercel/v0-sdk)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-v0-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vercel-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vercel-v0-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vercel-v0-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/vercel)
- [Integrations](https://vercel.com/marketplace)
- [Guide](https://vercel.com/guides)
- [Blog](https://vercel.com/blog)
- [Press Releases](https://vercel.com/press)
- [Changelog](https://vercel.com/changelog)
- [Documentation](https://vercel.com/docs)
- [Rate Limits](https://vercel.com/docs/rest-api/reference#rate-limits)
- [Versioning](https://vercel.com/docs/rest-api/reference#versioning)
- [Pagination](https://vercel.com/docs/rest-api/reference#pagination)
- [Support](https://vercel.com/help)
- [Pricing](https://vercel.com/pricing)
- [Templates](https://vercel.com/templates)
- [Login](https://vercel.com/login)
- [Sign Up](https://vercel.com/signup)
- [GitHub Organization](https://github.com/vercel/vercel)
- [Forum](https://community.vercel.com/)
- [Status Page](https://www.vercel-status.com)
- [Terms of Service](https://vercel.com/legal/terms)
- [Privacy Policy](https://vercel.com/legal/privacy-policy)
- [Security](https://security.vercel.com)
- [C L I](https://vercel.com/docs/cli)
- [SDK](https://vercel.com/docs/ai-sdk)
- [Security](https://vercel.com/docs/vercel-firewall)
- [Documentation](https://vercel.com/docs/vercel-firewall/firewall-api)
- [OpenAPI](https://openapi.vercel.sh/) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Security](https://vercel.com/security)
- [API Reference](https://vercel.com/docs/rest-api/reference)
- [Features](undefined)
- [M C P Server](https://github.com/vercel/next-devtools-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
