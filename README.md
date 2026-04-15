# 🦅 FemtoClaw Organization

**Industrial-grade AI agent runtime for deterministic, secure, and observable execution.**

Welcome to the official **FemtoClaw** organization. Our mission is to build the definitive execution authority for the next generation of autonomous agents. We provide the infrastructure layer that makes AI-driven automation safe, auditable, and production-ready for enterprise environments.

---

## 🌐 The Project Vision

The AI ecosystem is currently divided between powerful inference models and vulnerable execution environments. **FemtoClaw** bridges this gap by enforcing a strict separation between **Intent (Brain)** and **Authority (Runtime)**. 

By treating system capabilities as modular "Claws" and subject to normative policy enforcement, we ensure that autonomous agents can operate at scale without compromising the integrity of the host system or the broader network.

---

## 📦 Repository Map

Our ecosystem is organized into specialized repositories to maintain a minimal TCB (Trusted Computing Base) and ensure high maintainability.

### 1. Core Runtime
- **[femtoclaw](https://github.com/femtoclaw/femtoclaw)**: The primary Rust-based agent runtime. Implements the 10-phase execution lifecycle and the core control loop.

### 2. Normative Standards
- **[femtoclaw-spec](https://github.com/femtoclaw/femtoclaw-spec)**: The engineering specifications suite (FC-01 through FC-60). This is the source of truth for all runtime behavior.
- **[femtoclaw-protocol](https://github.com/femtoclaw/femtoclaw-protocol)**: Strict JSON schema definitions for agent-to-runtime communication.

### 3. Capability Ecosystem
- **[femtoclaw-claws](https://github.com/femtoclaw/femtoclaw-claws)**: The standard set of authorized system interfaces (Shell, Net, FS).
- **[femtoclaw-talons](https://github.com/femtoclaw/femtoclaw-talons)**: A vast library of community-built high-level integrations (Cloud, SCM, Databases).

### 4. Operations & Tooling
- **[femtoclaw-cli](https://github.com/femtoclaw/femtoclaw-cli)**: Interactive administrative REPL and operational command-line tool.
- **[femtoclaw-remote](https://github.com/femtoclaw/femtoclaw-remote)**: API server implementation for distributed clustering and remote management.
- **[femtoclaw-storage](https://github.com/femtoclaw/femtoclaw-storage)**: WAL-backed persistence layer for crash-resilient history.

---

## 🤝 Community & Contribution

FemtoClaw is a community-driven project. We believe that the safety standards for AI agents should be open, transparent, and built collaboratively.

### How to Get Involved:
1.  **Develop Talons**: Extend the ecosystem by building new tool integrations.
2.  **Harden the Core**: Contribute to the Rust runtime, focusing on performance and security invariants.
3.  **Refine Specifications**: Join the RFC process in the `femtoclaw-spec` repository to help shape the future of the standard.
4.  **Security Auditing**: Help us find and patch potential escape vectors in our capability sandboxes.

### Governance:
All official FemtoClaw projects are governed by the **FemtoClaw Engineering Authority**. We utilize an RFC (Request for Comments) process for any normative changes to the specifications or the core runtime behavior.

---

## 🛡️ Security Policy

Security is our primary property. If you discover a potential vulnerability in the runtime or any official capability, please refer to our **[Security Policy](./SECURITY.md)** for responsible disclosure guidelines. We prioritize the resolution of any issues that could bypass capability authorization or escape sandboxed execution.

---

## 📄 Licensing

The FemtoClaw project is committed to open-source software.
- **Code**: Licensed under **Apache 2.0**.
- **Specifications**: Licensed under **Apache 2.0**.
- **Branding**: Subject to the guidelines in the `femtoclaw-brand` repository.

Copyright © 2026 FemtoClaw Project.
