<div align="center">

<img src="https://raw.githubusercontent.com/peptimus/.github/main/profile/banner.png" alt="Peptimus" width="100%" />

# Peptimus

**Decentralized AI Peptide Design on Solana**

[![License](https://img.shields.io/badge/license-MIT-00f5ff?style=for-the-badge&labelColor=0a0f1c)](https://github.com/peptimus/peptimus/blob/main/LICENSE)
[![Solana](https://img.shields.io/badge/Solana-Mainnet-9945FF?style=for-the-badge&logo=solana&logoColor=white&labelColor=0a0f1c)](https://solana.com)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=0a0f1c)](https://www.typescriptlang.org)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=white&labelColor=0a0f1c)](https://react.dev)
[![pnpm](https://img.shields.io/badge/pnpm-workspace-F69220?style=for-the-badge&logo=pnpm&logoColor=white&labelColor=0a0f1c)](https://pnpm.io)

*Design. Evolve. Own. The future of peptide research is on-chain.*

</div>

---

## What is Peptimus?

Peptimus is an AI-powered platform for peptide sequence design, evolution, and on-chain IP ownership. Researchers describe a therapeutic goal in plain language — the AI generates candidate sequences, scores them for binding affinity, stability, novelty, and toxicity, then mints the best candidates as compressed NFTs on Solana at under $0.001 per mint.

---

## How it works

```mermaid
flowchart LR
    A([Researcher]) -->|Describe goal| B[AI Studio]
    B -->|AI Engine| C[Peptide Candidates]
    C -->|Select & Mint| D[IP-NFT on Solana]
    D -->|Publish| E[Community Feed]

    style A fill:#00f5ff,color:#0a0f1c,stroke:none
    style B fill:#8b5cf6,color:#fff,stroke:none
    style C fill:#1a2035,color:#00ff9f,stroke:none
    style D fill:#9945FF,color:#fff,stroke:none
    style E fill:#1a2035,color:#fff,stroke:none
```

---

## Repositories

| Repository | Description | Stack |
|---|---|---|
| [peptimus](https://github.com/peptimus/peptimus) | Main web application | React 18 · Vite · Tailwind · Three.js · Framer Motion |
| [peptimus-api](https://github.com/peptimus/peptimus-api) | REST API + database layer | Express 5 · PostgreSQL · Drizzle ORM |
| [peptimus-shared](https://github.com/peptimus/peptimus-shared) | Shared TypeScript packages | OpenAPI Spec · Zod v4 · TanStack Query |
| [peptimus-infra](https://github.com/peptimus/peptimus-infra) | Monorepo root & infrastructure | pnpm workspace · GitHub Actions · Node.js 24 |

---

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React 18, Vite, Tailwind CSS, Framer Motion, React Three Fiber, Wouter, Zustand |
| **Blockchain** | Solana Mainnet, Metaplex Bubblegum v5, Jupiter Unified Wallet, cNFT IP-NFT |
| **Backend** | Express 5, PostgreSQL, Drizzle ORM, Pino Logger |
| **Shared** | TypeScript 5.9, OpenAPI Spec, Zod v4, TanStack Query |
| **Infra** | pnpm workspace, Node.js 24, GitHub Actions CI |

---

## Roadmap

| Period | Milestone |
|---|---|
| Q2 2026 | AI Peptide Design Studio · IP-NFT Minting on Solana · Community Feed |
| Q3 2026 | PTMS Token Launch · Bounty Program · Peptide Comparison Tool |
| Q4 2026 | DAO Governance · Smart Contract Bounty Validation · Reputation System |
| Q1 2027 | Partner Protocol Integrations · Cross-chain IP-NFT Bridging · Enterprise API |

---

## Cost per Peptide

| Action | Cost |
|---|---|
| AI Design (~1100 tokens) | ~$0.001 |
| DB Storage (1 row, ~500 bytes) | ~$0.0001 |
| NFT Mint (Solana cNFT via Bubblegum) | ~$0.001 |
| **Total end-to-end** | **~$0.002** |

---

<div align="center">

[![Website](https://img.shields.io/badge/peptimus.xyz-00f5ff?style=for-the-badge&logo=googlechrome&logoColor=0a0f1c)](https://peptimus.xyz)
[![App](https://img.shields.io/badge/peptimus.xyz/app-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://peptimus.xyz/app)
[![X](https://img.shields.io/badge/Follow_on_X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/peptimusdev)

**Built by [peptimusdev](https://github.com/peptimusdev)**

</div>
