# 🦅 FemtoClaw Organization

> **Lightweight. Rust-based. Cryptoeconomically Aligned.**

Welcome to the official home of **FemtoClaw**, the next evolution in the Claw automation lineage (OpenClaw → PicoClaw → **FemtoClaw**). We build privacy-first AI agents designed for the edge, secured by Rust, and coordinated by the $FEMTO token.

---

## 🏗 Core Architecture

FemtoClaw agents are modular by design, separating cognition from execution:

| Component | Description | Status |
|-----------|-------------|--------|
| **Core** | Rust-based agent loop & safety sandbox | 🟢 Stable |
| **Brain** | Modular LLM interface (Local Ollama / Remote API) | 🟢 Stable |
| **Memory** | Short-term context + Long-term vector storage | 🟡 Beta |
| **Claws** | Executable tools (Web, Shell, API) | 🟢 Stable |
| **Token** | $FEMTO cryptoeconomic layer (Solana/EVM) | 🟡 Testnet |

---

## 📦 Key Repositories

| Repository | Description |
|------------|-------------|
| [`femtoclaw/core`](https://github.com/femtoclaw/femtoclaw) | The main Rust agent binary & SDK |
| [`femtoclaw/protocol`](https://github.com/femtoclaw/protocol) | Smart contracts ($FEMTO token, staking, registry) |
| [`femtoclaw/docs`](https://github.com/femtoclaw/docs) | Documentation, whitepaper, and specs |
| [`femtoclaw/claws`](https://github.com/femtoclaw/claws) | Community-contributed tool library |
| [`femtoclaw/brand`](https://github.com/femtoclaw/brand) | Logos, assets, and brand guidelines |

---

## 🚀 Quick Start

```bash
# Install the FemtoClaw CLI
cargo install femtoclaw

# Initialize a new agent
femtoclaw init my-agent

# Run with local brain
femtoclaw run --brain ollama --model llama3
