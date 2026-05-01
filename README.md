# Flatcar Container Linux (flatcar-container-linux)
Flatcar Container Linux is a CNCF incubating minimal, immutable Linux distribution designed for running containers. It provides automatic atomic updates through the Nebraska update server, ensuring nodes stay secure and consistent. Flatcar supports Kubernetes deployments on bare metal, cloud, and virtual environments with a focus on security and operational simplicity.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/flatcar-container-linux/refs/heads/main/apis.yml)

## Scope
- **Type:** Index
- **Position:** Producer
- **Access:** Open Source

## Tags:
 - Cloud Native, Containers, Immutable Infrastructure, Incubating, Linux, Operating System

## Timestamps
- **Created:** 2026-03-16
- **Modified:** 2026-04-28

## APIs

### Flatcar Nebraska Update API
Nebraska is the update management server for Flatcar Container Linux. It exposes a REST API for managing update applications, packages, channels, groups, instances, and activity. Flatcar instances poll Nebraska using the Omaha protocol for controlled rollouts, version pinning, and update monitoring across fleets of Flatcar nodes.

**Human URL:** [https://www.flatcar.org/docs/latest/nebraska/](https://www.flatcar.org/docs/latest/nebraska/)

**Base URL:** https://nebraska.flatcar-linux.org/api

#### Tags:
 - Activity, Applications, Channels, Fleet Management, Groups, Instances, Omaha Protocol, Packages, Updates

#### Properties
- [Documentation](https://www.flatcar.org/docs/latest/nebraska/)
- [OpenAPI](openapi/nebraska-update-api-openapi.yml)
- [SourceCode](https://github.com/flatcar/nebraska)

## Common Properties
- [Website](https://www.flatcar.org)
- [Documentation](https://www.flatcar.org/docs/latest/)
- [GitHubOrganization](https://github.com/flatcar)
- [SourceCode](https://github.com/flatcar/flatcar)
- [NebraskaSource](https://github.com/flatcar/nebraska)
- [Releases](https://www.flatcar.org/releases/)
- [Community](https://www.flatcar.org/community/)

## Artifacts

### OpenAPI
- [Flatcar Nebraska Update API](openapi/nebraska-update-api-openapi.yml)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
