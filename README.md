# Privinux

**Linux-native Identity and Privileged Access Management**  
_No Active Directory. No Windows. No legacy bloat._

Privinux is a modern IAM and PAM platform designed specifically for **Linux-first infrastructure**.  
It enables organizations to manage identity, authentication, and privileged access across Linux servers, cloud workloads, and Kubernetes environments—**without requiring Microsoft Active Directory**.

---

## Why Privinux?

Modern infrastructure runs on Linux, but identity systems still depend on legacy, Windows-centric tooling.

Privinux exists to fix that.

- Most enterprise IAM/PAM solutions assume Active Directory
- OpenLDAP is difficult to operate and scale securely
- Windows infrastructure is often deployed solely for identity compatibility

Privinux removes this dependency by providing a **Linux-native identity and privilege control plane**, built on open standards and modern security principles.

---

## Design Principles

Privinux is built with a few strong opinions:

- **Linux-first by design**  
  Built for Linux systems, not adapted from Windows tooling.

- **AD-free architecture**  
  No Microsoft Active Directory required—ever.

- **Least privilege by default**  
  Identity and access are scoped, time-bound, and auditable.

- **Infrastructure-grade**  
  Simple, predictable, automation-friendly, and boring in the best way.

- **Cloud & Kubernetes ready**  
  Designed for modern environments from day one.

---

## What Privinux Provides (High Level)

### Identity & Access Management
- Centralized identity for Linux environments
- Modern authentication using open standards (OIDC, OAuth 2.0, SAML)
- LDAP-compatible interfaces for legacy systems
- Multi-factor authentication support
- Role and policy-based access control

### Privileged Access Management
- Secure SSH access without shared credentials
- Just-in-time privilege elevation
- SSH certificate-based authentication
- Command-level auditing and session logging
- Strong audit trails for compliance and security review

### Native Linux Integration
- PAM and NSS integration
- Works across on-prem, cloud, and containerized workloads
- Designed for automation and GitOps workflows

---

## Target Users

Privinux is built for:

- Cloud-native startups and SaaS companies
- Linux-heavy enterprises
- DevOps and SRE teams
- Security teams reducing Windows dependency
- Organizations adopting zero trust and least privilege models

---

## Project Status

🚧 **Early-stage / active development**

This repository currently represents:
- Project vision and direction
- Early design and architectural exploration
- Public-facing documentation

Code will be published incrementally as the project matures.

---

## Roadmap (High-Level)

- Core identity service
- Linux PAM/NSS integration
- SSH certificate authority
- Audit and logging pipeline
- Kubernetes-native integrations
- Enterprise governance features

Details will evolve as development progresses.

---

## Open Source & Licensing

Privinux is licensed under the **Apache License 2.0**.

This allows:
- Open collaboration
- Enterprise adoption
- Commercial extensions in the future

See the `LICENSE` file for details.

---

## Get Involved

Privinux is in its early days.  
Feedback, discussion, and thoughtful contributions are welcome.

- Follow development here on GitHub
- Open an issue for ideas or questions
- Reach out if you're interested in early access or collaboration

---

## Vision

Privinux aims to become the **default identity and privileged access platform for Linux environments**, analogous to what Active Directory historically represented for Windows—but aligned with modern infrastructure and security realities.

---

**Privinux — Identity, reimagined for Linux**
