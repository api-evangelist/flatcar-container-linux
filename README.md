# Flatcar Container Linux (flatcar-container-linux)

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

Flatcar Container Linux is a CNCF incubating minimal, immutable Linux distribution designed for running containers. It provides automatic atomic updates through the Nebraska update server, ensuring nodes stay secure and consistent. Flatcar supports Kubernetes deployments on bare metal, cloud, and virtual environments with a focus on security and operational simplicity.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** Open Source

## Tags

- Cloud Native
- Containers
- Immutable Infrastructure
- Incubating
- Linux
- Operating System

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Flatcar Nebraska Update API

Nebraska is the update management server for Flatcar Container Linux. It exposes a REST API for managing update applications, packages, channels, groups, instances, and activity. Flatcar instances poll Nebraska using the Omaha protocol for controlled rollouts, version pinning, and update monitoring across fleets of Flatcar nodes.

- **Human URL:** [https://www.flatcar.org/docs/latest/nebraska/](https://www.flatcar.org/docs/latest/nebraska/)
- **Base URL:** `https://nebraska.flatcar-linux.org/api`

#### Tags

- Activity
- Applications
- Channels
- Fleet Management
- Groups
- Instances
- Omaha Protocol
- Packages
- Updates

#### Properties

- [Documentation](https://www.flatcar.org/docs/latest/nebraska/)
- [OpenAPI](openapi/nebraska-update-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/nebraska-update-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/nebraska-update-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Source Code](https://github.com/flatcar/nebraska)

## Common Properties

- [Website](https://www.flatcar.org)
- [Documentation](https://www.flatcar.org/docs/latest/)
- [GitHub Organization](https://github.com/flatcar)
- [Source Code](https://github.com/flatcar/flatcar)
- [Nebraska Source](https://github.com/flatcar/nebraska)
- [Releases](https://www.flatcar.org/releases/)
- [Community](https://www.flatcar.org/community/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
