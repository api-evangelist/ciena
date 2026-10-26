# Ciena (ciena)

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

Ciena Corporation is a global networking equipment, software, and services vendor focused on optical and packet networking, SDN, and service automation. This index covers Ciena's open APIs across the Blue Planet automation platform, the Ciena MCP (Manage, Control, and Plan) NMS, and the Emulation Cloud developer environment, exposing TM Forum Open APIs, MEF Lifecycle Service Orchestration (LSO) APIs (Legato, Sonata), and ONAP-aligned policy controls for telecom carriers and managed service providers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ciena/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- MEF
- NETCONF
- Network Automation
- Network Management
- Optical
- RESTCONF
- SDN
- Telecom
- TM Forum

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-05-19

## APIs

### Ciena Blue Planet Open API

Ciena Blue Planet provides open APIs for multi-layer SDN network management and automation. The platform supports TM Forum Open APIs, MEF Lifecycle Service Orchestration (LSO) APIs including Legato and Sonata, and integrates with ONAP policy frameworks. APIs enable network topology management, circuit provisioning, performance monitoring, and network operations automation for telecom carriers.

- **Human URL:** [https://www.blueplanet.com/technology/open-apis.html](https://www.blueplanet.com/technology/open-apis.html)
- **Base URL:** `https://api.blueplanet.com/bpocore/market/api/v1`

#### Tags

- MEF
- Network Automation
- Optical
- SDN
- Telecom
- TM Forum

#### Properties

- [Documentation](https://www.blueplanet.com/technology/open-apis.html)
- [Portal](https://developer.blueplanet.com)
- [Blog](https://www.blueplanet.com/blog)
- [Support](https://www.blueplanet.com/support)
- [Contact](https://www.blueplanet.com/contact)
- [OpenAPI](openapi/ciena-blue-planet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ciena-blue-planet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ciena-blue-planet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ciena MCP (Manage, Control and Plan) API

Ciena's Manage, Control and Plan (MCP) is a multi-layer Software Defined Networking (SDN) and Network Management System (NMS) platform. The MCP REST and RESTCONF APIs enable network-aware management operations for optical and packet networks including topology discovery, circuit provisioning, configuration management, and performance data retrieval.

- **Human URL:** [https://software.ciena.com/releasenotes/MCP-DOCS_5.2-217/build/site/mcp-docs/user-guide/Overview.html](https://software.ciena.com/releasenotes/MCP-DOCS_5.2-217/build/site/mcp-docs/user-guide/Overview.html)
- **Base URL:** `https://api.ciena.com/mcp`

#### Tags

- NETCONF
- Network Management
- RESTCONF
- SDN
- Telecom

#### Properties

- [Documentation](https://software.ciena.com/releasenotes/MCP-DOCS_5.2-217/build/site/mcp-docs/user-guide/Overview.html)
- [Postman Collection](collections/ciena-blue-planet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ciena-blue-planet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ciena Emulation Cloud API

Ciena Emulation Cloud is an open application development environment enabling developers to create, test, and fine-tune custom applications against full API definitions without requiring physical infrastructure. Provides access to complete API documentation, tutorials, and sample code for Ciena network platforms.

- **Human URL:** [https://www.ciena.com/products/emulation-cloud](https://www.ciena.com/products/emulation-cloud)
- **Base URL:** `https://developer.ciena.com`

#### Tags

- Developer Tools
- SDN
- Telecom
- Testing

#### Properties

- [Documentation](https://www.ciena.com/products/emulation-cloud)
- [Portal](https://developer.ciena.com/)
- [Postman Collection](collections/ciena-blue-planet.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ciena-blue-planet.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ciena)
- [LinkedIn](https://www.linkedin.com/company/ciena)
- [Website](https://www.ciena.com/)
- [Developer Portal](https://developer.ciena.com/)
- [Portal](https://developer.blueplanet.com)
- [Documentation](https://www.blueplanet.com/technology/open-apis.html)
- [Blog](https://www.blueplanet.com/blog)
- [Support](https://www.blueplanet.com/support)
- [Privacy Policy](https://www.ciena.com/about/corporate-governance/privacy-policy)
- [Terms of Service](https://www.ciena.com/customers/terms-and-conditions)
- [Community](https://my.ciena.com/CienaPortal/s/blue-planet)
- [Git Hub Org](https://git.blueplanet.com)
- [OpenAPI](openapi/ciena-blue-planet-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](json-ld/ciena-context.jsonld)
- [JSON Schema](json-schema/ciena-network-service-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](spectral/ciena-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://developer.ciena.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
