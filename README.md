# Atlassian Confluence (atlassian-confluence)

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

Atlassian Confluence is a team collaboration and wiki platform for creating, organizing, and discussing work with your team. It provides REST APIs (v1 and v2) and a GraphQL API for managing content, spaces, pages, users, labels, and search across Confluence Cloud deployments, enabling automation, app development, and integration with enterprise workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/atlassian-confluence/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/atlassian-confluence/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Atlassian
- Collaboration
- Content Management
- Documentation
- Knowledge Management
- Wiki

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Confluence Cloud REST API

The primary REST API for Confluence Cloud, providing access to content, spaces, users, and more.

- **Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/](https://developer.atlassian.com/cloud/confluence/rest/)
- **Base URL:** `https://your-domain.atlassian.net/wiki/rest/api`

#### Tags

- Content
- Pages
- REST
- Spaces

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v1/intro/)
- [OpenAPI](https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.atlassian.com/cloud/confluence/authentication/)
- [Getting Started](https://developer.atlassian.com/cloud/confluence/getting-started/)
- [Postman Collection](collections/atlassian-confluence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/atlassian-confluence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Confluence Cloud REST API V2

The next generation REST API for Confluence Cloud with improved performance and new capabilities.

- **Human URL:** [https://developer.atlassian.com/cloud/confluence/rest/v2/intro/](https://developer.atlassian.com/cloud/confluence/rest/v2/intro/)
- **Base URL:** `https://your-domain.atlassian.net/wiki/api/v2`

#### Tags

- Content
- Pages
- REST
- Spaces

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/rest/v2/intro/)
- [OpenAPI](https://dac-static.atlassian.com/cloud/confluence/openapi-v2.v3.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/atlassian-confluence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/atlassian-confluence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Confluence Cloud GraphQL API

The Confluence Cloud GraphQL API provides flexible querying and mutation capabilities for Confluence content, spaces, pages, and user data using OAuth 2.0 authentication.

- **Human URL:** [https://developer.atlassian.com/cloud/confluence/graphql/](https://developer.atlassian.com/cloud/confluence/graphql/)
- **Base URL:** `https://api.atlassian.com/graphql`

#### Tags

- Content
- GraphQL
- Pages
- Spaces

#### Properties

- [Documentation](https://developer.atlassian.com/cloud/confluence/graphql/)
- [Postman Collection](collections/atlassian-confluence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/atlassian-confluence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/confluence-by-atlassian)
- [Website](https://www.atlassian.com/software/confluence)
- [Documentation](https://developer.atlassian.com/cloud/confluence/)
- [Getting Started](https://developer.atlassian.com/cloud/confluence/getting-started/)
- [Authentication](https://developer.atlassian.com/cloud/confluence/oauth-2-3lo-apps/)
- [Changelog](https://developer.atlassian.com/cloud/confluence/changelog/)
- [Status Page](https://status.atlassian.com/)
- [Support](https://support.atlassian.com/)
- [Community](https://community.atlassian.com/)
- [Terms of Service](https://www.atlassian.com/legal/cloud-terms-of-service)
- [Privacy Policy](https://www.atlassian.com/legal/privacy-policy)
- [GitHub Organization](https://github.com/atlassian)
- [Rate Limits](https://developer.atlassian.com/cloud/confluence/rate-limiting/)
- [Blog](https://developer.atlassian.com/blog/)
- [Pricing](https://www.atlassian.com/software/confluence/pricing)
- [Sign Up](https://www.atlassian.com/software/confluence)
- [SDK](https://developer.atlassian.com/platform/forge/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
