# SleekFlow (sleekflow)

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

SleekFlow is an omnichannel social-commerce and customer-engagement platform that unifies WhatsApp, Facebook Messenger, Instagram, WeChat, LINE, SMS, and live chat into a single inbox with automation, broadcast, and AI. The SleekFlow Platform API exposes contacts, conversations, messaging, companies, lists, staff and teams, and webhooks for building custom integrations on top of the platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sleekflow/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sleekflow/refs/heads/main/apis.yml)

## Tags

- Messaging
- Omnichannel
- WhatsApp
- Customer Engagement
- Social Commerce
- Automation

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### SleekFlow Contacts API

Create, update, retrieve, search, and delete contacts, including dynamic field selection, so customer records can be synced between SleekFlow and external systems.

- **Human URL:** [https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts](https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Contacts
- CRM
- Customers

#### Properties

- [Documentation](https://help.sleekflow.io/en_US/integrations/platform-api-integration)
- [API Reference](https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sleekflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sleekflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SleekFlow Conversations & Messaging API

Send messages, files, and internal notes across WhatsApp and other channels, check the WhatsApp Business conversation window, retrieve conversations and messages, and update a conversation's assignee in the shared inbox.

- **Human URL:** [https://apidoc.sleekflow.io/docs/platform-api/9ty13q0r571om-messaging](https://apidoc.sleekflow.io/docs/platform-api/9ty13q0r571om-messaging)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Conversations
- Messaging
- Inbox
- WhatsApp

#### Properties

- [API Reference](https://apidoc.sleekflow.io/docs/platform-api/9ty13q0r571om-messaging)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sleekflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sleekflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SleekFlow Companies API

Manage company records and associate contacts with companies for B2B engagement workflows.

- **Human URL:** [https://apidoc.sleekflow.io/docs/platform-api/nijbjgxrs4s50-sleek-flow-platform-api](https://apidoc.sleekflow.io/docs/platform-api/nijbjgxrs4s50-sleek-flow-platform-api)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Companies
- Organizations
- CRM

#### Properties

- [API Reference](https://apidoc.sleekflow.io/docs/platform-api/nijbjgxrs4s50-sleek-flow-platform-api)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sleekflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sleekflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SleekFlow Lists API

Create and manage contact lists, retrieve list details, and add or remove contacts from lists for segmentation and broadcast targeting.

- **Human URL:** [https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts](https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Lists
- Segmentation
- Contacts

#### Properties

- [API Reference](https://apidoc.sleekflow.io/docs/platform-api/3z6iu3fo5evix-contacts)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sleekflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sleekflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SleekFlow Staff & Teams API

List and manage staff and teams, assign staff to teams, and read per-staff conversation summaries for workforce and routing management.

- **Human URL:** [https://apidoc.sleekflow.io/docs/platform-api/t21aeu2xvtiw6-staff-and-team](https://apidoc.sleekflow.io/docs/platform-api/t21aeu2xvtiw6-staff-and-team)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Staff
- Teams
- Users

#### Properties

- [API Reference](https://apidoc.sleekflow.io/docs/platform-api/t21aeu2xvtiw6-staff-and-team)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sleekflow.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sleekflow.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SleekFlow Webhooks API

Register webhook subscriptions to receive real-time HTTP callbacks for new and updated contacts and incoming messages, enabling event-driven integrations.

- **Human URL:** [https://help.sleekflow.io/en_US/integrations/platform-api-integration](https://help.sleekflow.io/en_US/integrations/platform-api-integration)
- **Base URL:** `https://api.sleekflow.io`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://help.sleekflow.io/en_US/integrations/platform-api-integration)
- [OpenAPI](openapi/sleekflow-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Review](review.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sleekflow)
- [Website](https://sleekflow.io)
- [Documentation](https://apidoc.sleekflow.io/docs/platform-api/nijbjgxrs4s50-sleek-flow-platform-api)
- [Plans](plans/sleekflow-plans-pricing.yml)
- [Rate Limits](rate-limits/sleekflow-rate-limits.yml)
- [Fin Ops](finops/sleekflow-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
