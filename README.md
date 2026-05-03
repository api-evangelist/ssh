# SSH

SSH (Secure Shell) is a cryptographic network protocol for secure remote login, command execution, and file transfer between computers over unsecured networks. It provides strong encryption, authentication, and data integrity, replacing insecure protocols like Telnet and rlogin. SSH is a fundamental tool for system administration, DevOps, and secure infrastructure access.

- **Website:** https://www.openssh.com/
- **Documentation:** https://www.openssh.com/manual.html
- **GitHub:** https://github.com/openssh

## APIs

### OpenSSH Key Management API

Programmatic interface for SSH key management, certificate signing, authorized keys administration, and known hosts management. Enables infrastructure teams to manage SSH access at scale using certificate-based authentication.

- **Base URL:** https://api.openssh.example.com/v1
- **Documentation:** https://www.openssh.com/manual.html
- **OpenAPI:** [ssh-key-management-openapi.yml](openapi/ssh-key-management-openapi.yml)

### Teleport Access Management API

Teleport is a modern SSH infrastructure access platform providing certificate-based authentication, session recording, audit logging, and role-based access control.

- **Documentation:** https://goteleport.com/docs/

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [ssh-key-management-openapi.yml](openapi/ssh-key-management-openapi.yml) | SSH key management and certificate authority API |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [ssh-rules.yml](rules/ssh-rules.yml) | Spectral rules for SSH management API conventions |

### Capabilities

#### Workflow Capabilities

| Capability | Description |
|-----------|-------------|
| [key-management.yaml](capabilities/key-management.yaml) | Unified SSH key lifecycle and certificate management workflow |

#### Shared Definitions

| Shared | Description |
|--------|-------------|
| [key-management.yaml](capabilities/shared/key-management.yaml) | SSH Key Management API consumer definition |

### JSON Schema

| Schema | Description |
|--------|-------------|
| [ssh-key-schema.json](json-schema/ssh-key-schema.json) | SSH key and certificate entity schema |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [ssh-key-structure.json](json-structure/ssh-key-structure.json) | SSH key management structure documentation |

### JSON-LD

| Context | Description |
|---------|-------------|
| [ssh-context.jsonld](json-ld/ssh-context.jsonld) | JSON-LD context for SSH security vocabulary |

### Examples

| Example | Description |
|---------|-------------|
| [ssh-list-keys-example.json](examples/ssh-list-keys-example.json) | List registered SSH keys example |
| [ssh-sign-certificate-example.json](examples/ssh-sign-certificate-example.json) | Sign SSH certificate with CA example |

### Vocabulary

| Vocabulary | Description |
|-----------|-------------|
| [ssh-vocabulary.yml](vocabulary/ssh-vocabulary.yml) | SSH protocol vocabulary and terminology |
