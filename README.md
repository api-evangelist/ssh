# SSH (ssh)

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

SSH (Secure Shell) is a cryptographic network protocol for secure remote login, command execution, and file transfer between computers over unsecured networks. It provides strong encryption, authentication, and data integrity, replacing insecure protocols like Telnet and rlogin. SSH is a fundamental tool for system administration, DevOps, and secure infrastructure access. Multiple vendors provide SSH client libraries, server implementations, and management APIs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- SSH
- Secure Shell
- Remote Access
- Cryptography
- Network Security
- System Administration

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### OpenSSH Key Management API

OpenSSH is the premier open-source SSH implementation. While SSH itself is a protocol, OpenSSH provides programmatic interfaces for key management, authorized_keys configuration, known_hosts management, and integration with PAM and certificate authorities. SSH certificate authorities enable large-scale key management via short-lived certificates.

- **Human URL:** [https://www.openssh.com/](https://www.openssh.com/)
- **Base URL:** `https://api.openssh.example.com/v1`

#### Tags

- SSH
- OpenSSH
- Key Management
- Certificate Authority
- Authentication

#### Properties

- [Documentation](https://www.openssh.com/manual.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ssh-key-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssh-key-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Teleport Access Management API

Teleport is a modern SSH infrastructure access platform providing certificate-based authentication, session recording, audit logging, and role-based access control for SSH, Kubernetes, databases, and web applications. Teleport's API enables programmatic management of users, roles, certificates, and access policies.

- **Human URL:** [https://goteleport.com/](https://goteleport.com/)
- **Base URL:** `https://teleport.example.com/v1`

#### Tags

- SSH
- Access Management
- Certificate Authority
- Zero Trust
- Privileged Access

#### Properties

- [Documentation](https://goteleport.com/docs/)
- [Postman Collection](collections/ssh-key-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ssh-key-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.openssh.com/)
- [Documentation](https://www.openssh.com/manual.html)
- [GitHub Organization](https://github.com/openssh)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/openapi/ssh-key-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-schema/ssh-key-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-structure/ssh-key-structure.json)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/json-ld/ssh-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/rules/ssh-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/ssh/refs/heads/main/vocabulary/ssh-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
