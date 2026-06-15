# SSH (ssh)

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
