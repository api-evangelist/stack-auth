# Stack Auth (stack-auth)

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
