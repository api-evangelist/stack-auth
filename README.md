# Stack Auth (stack-auth)

Stack Auth is an open-source authentication and user management platform positioned as a self-hostable alternative to closed-source providers like Clerk and Auth0. It bundles password, OAuth / SSO, and two-factor sign-in flows with organizations, teams, role-based access control, impersonation, webhooks, and pre-built UI components built on shadcn/ui (or a headless SDK). Stack Auth is available as a hosted SaaS at app.stack-auth.com and as a self-hosted deployment from the stack-auth/stack monorepo on GitHub. Authentication is JWT-based. Y Combinator-backed.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stack-auth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stack-auth/refs/heads/main/apis.yml)

## Tags

- Authentication
- User Management
- Open Source
- Self-Hosted
- Identity
- Organizations
- RBAC

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Stack Auth REST API

REST API for managing users, sessions, OAuth providers, teams, organizations, permissions, and webhooks. Used by Stack Auth's own SDKs and available for custom backend integrations. JWT-based authentication with server / publishable / secret API keys per project.

- **Human URL:** [https://docs.stack-auth.com/rest-api/overview](https://docs.stack-auth.com/rest-api/overview)
- **Base URL:** `https://api.stack-auth.com`

#### Tags

- REST
- Authentication
- Users
- Teams

#### Properties

- [Documentation](https://docs.stack-auth.com/rest-api/overview)
- [Postman Collection](collections/stack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stack Auth Webhooks

Outbound webhook events for user lifecycle, team / organization membership, and permission changes. Customers register endpoint URLs and verify delivery via signed payloads.

- **Human URL:** [https://docs.stack-auth.com/concepts/webhooks](https://docs.stack-auth.com/concepts/webhooks)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://docs.stack-auth.com/concepts/webhooks)
- [Postman Collection](collections/stack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stack Auth React / Next.js SDK

Frontend SDK distributed as @stackframe/stack on npm. Provides React components, hooks, and Next.js App Router middleware for sign-in, sign-up, account settings, and team / organization management. Headless mode supported for custom UI.

- **Human URL:** [https://docs.stack-auth.com/sdk/overview](https://docs.stack-auth.com/sdk/overview)
- **Base URL:** `https://github.com/stack-auth/stack`

#### Tags

- SDK
- React
- Next.js
- Frontend

#### Properties

- [Documentation](https://docs.stack-auth.com/sdk/overview)
- [Repository](https://github.com/stack-auth/stack)
- [Postman Collection](collections/stack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stack Auth CLI

Project bootstrap CLI distributed as @stackframe/init-stack on npm, invoked with `npx @stackframe/init-stack@latest` to wire Stack Auth into a new or existing project.

- **Human URL:** [https://docs.stack-auth.com/getting-started/setup](https://docs.stack-auth.com/getting-started/setup)
- **Base URL:** `https://github.com/stack-auth/stack`

#### Tags

- CLI
- Tooling

#### Properties

- [Documentation](https://docs.stack-auth.com/getting-started/setup)
- [Postman Collection](collections/stack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stack Auth Self-Hosted (stack-auth/stack)

Open-source monorepo containing the Stack Auth backend (Next.js + Postgres) and dashboard. Deployable on customer infrastructure as an alternative to the hosted SaaS at app.stack-auth.com.

- **Human URL:** [https://github.com/stack-auth/stack](https://github.com/stack-auth/stack)
- **Base URL:** `https://github.com/stack-auth/stack`

#### Tags

- Open Source
- Self-Hosted
- Repository

#### Properties

- [Repository](https://github.com/stack-auth/stack)
- [Postman Collection](collections/stack-auth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stack-auth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://stack-auth.com/)
- [Documentation](https://docs.stack-auth.com/)
- [Git Hub](https://github.com/stack-auth)
- [Dashboard](https://app.stack-auth.com/)
- [Pricing](https://stack-auth.com/pricing)
- [Blog](https://stack-auth.com/blog)
- [L L Ms Txt](https://docs.stack-auth.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
