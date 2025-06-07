![github readme banner](https://github.com/user-attachments/assets/a9250cb2-51ef-41c2-974d-74ed830e24bf)



## 🧠 What is Nuwa?
Nuwa is an open protocol and developer ecosystem that enables the creation of Super Agents — AI-powered assistants that understand you, remember your preferences, and take action across digital services on your behalf.

Less friction for users; more reach and direct monetization for your tools and services.

## 🚀 Why Nuwa?
Today’s internet is app-centric:
- **Fragmented**: Tasks span dozens of apps and interfaces. Nothing shares memory. Users juggle logins, permissions, and context — even across AI tools.
- **Repetitive**: The same intent must be re-entered across tools. Planning a trip? You’ll repeat yourself to calendars, search engines, emails, and maps — even if you’re using different AIs for each.
- **Inefficient**: Switching between interfaces, navigating UIs, and stitching together workflows burns time and attention. Even with today’s powerful AI, users are stuck managing multiple assistants with no shared state or coordination.

Nuwa flips the model: agent-first, protocol-powered, and user-aligned.
- **For users**: One agent that remembers you and acts for you. No more app hopping or manual stitching.
- **For developers**: Build once as a Cap, reach every agent, and earn per use — no app store, no UI burden.
- **For the ecosystem**: Open, interoperable, and trust-aligned. Agents call any service, not just what one platform allows.


## 🔧 Core Components
**🧠 Nuwa Agent Framework**
Your local, intelligent runtime that represents you. Nuwa agent holds your memory, identity, and wallet. It parses your intent, orchestrates Cap execution, manages payments, and logs outcomes — across all services and contexts.

**🔌 Agent Capability Protocol (ACP)**
A standard for defining Caps — agent-callable capabilities with structured inputs, outputs, permissions, and pricing. ACP makes services interoperable and composable, like building blocks for agents.

**🌐 Cap Ecosystem**
A decentralized network of developer-built Caps. Each Cap is a standalone function — accessible by any agent, priced per use, and stackable into complex workflows. No app stores. No lock-in.

## 📂 Repository Structure

This repository is a monorepo containing various components of the Nuwa Protocol. Here's a brief overview of the key directories:

*   **`nips/`**: [Nuwa Improvement Proposals](nips/README.md). This is where the design and specification of the Nuwa protocol and its core components are discussed and documented.
*   **`contracts/`**: Contains information and potentially ABIs related to Nuwa smart contracts.
*   **`nuwa-agent/`**: The Nuwa client agent implementation.
*   **`nuwa-kit/`**: [Development Kits](./nuwa-kit/README.md) for building applications and services on Nuwa. This includes client SDKs and service development frameworks for various languages (e.g., TypeScript, Python).
*   **`nuwa-services/`**: Reference implementations of key [Nuwa Services](./nuwa/blob/main/README.md) (e.g., Custodian Service, LLM Proxy Service).
*   **`nuwa-script/`**: (Experimental) A purpose-built scripting language for AI agents.

Please refer to the `README.md` file within each directory for more specific details.

## 🤝 How to Contribute

We warmly welcome contributions to the Nuwa Protocol! Whether you're interested in contributing to the core protocol, developing new Caps, improving SDKs, or helping with documentation, your input is valuable.

To get started, please read our **[Contributing Guidelines (CONTRIBUTING.md)](./CONTRIBUTING.md)**.

This document provides detailed information on:
- How to report bugs and suggest enhancements.
- The process for submitting pull requests.
- Development setup and coding guidelines.
- The Nuwa Improvement Proposal (NIP) process for significant changes.

You can find open issues suitable for new contributors by looking for the [good first issue](https://github.com/rooch-network/nuwa/labels/good%20first%20issue) or [help wanted](https://github.com/rooch-network/nuwa/labels/help%20wanted) labels in our GitHub issues.

## 🧭 Roadmap Highlights
- ✅ MVP Client with memory + Cap execution
- 🛠️ Cap SDK & Developer Onboarding
- 🔒 Staking & Trust Layer for Caps
- 🌐 Enterprise-Grade Integrations

## Early Explorations
- [On-Chain AI Agent]() - an on-chain AI Agent framework
- [Nuwa Script]() - a purpose-built scripting language designed for AI agents to express workflows
- [Agent-Based Campaign]() - an experimental agent based campaign app

## 🗣️ License
MIT — because open infrastructure should stay open.

