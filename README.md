# Flatcar Container Linux (flatcar-container-linux)

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
