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

## Overview

Peptimus is a bio-protocol for AI-driven peptide molecule design and on-chain IP ownership. Researchers describe a therapeutic goal in plain language; the AI generates candidate sequences, scores them across four dimensions (binding affinity, stability, novelty, toxicity), then mints the best candidates as IP-NFTs on Solana, creating verifiable on-chain ownership of each discovered molecule as a transferable intellectual property asset.

The platform follows the emerging BioNFT standard where each minted molecule NFT represents a discrete, ownable unit of biological IP, bridging computational drug discovery with decentralized science (DeSci) infrastructure.

## How It Works

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

## Repositories

| Repository | Description | Stack |
|---|---|---|
| [peptimus](https://github.com/peptimus/peptimus) | Main web application | React 18 · Vite · Tailwind · Three.js · Framer Motion |
| [peptimus-api](https://github.com/peptimus/peptimus-api) | REST API and database layer | Express 5 · PostgreSQL · Drizzle ORM |
| [peptimus-shared](https://github.com/peptimus/peptimus-shared) | Shared TypeScript packages | OpenAPI Spec · Zod v4 · TanStack Query |
| [peptimus-infra](https://github.com/peptimus/peptimus-infra) | Monorepo root and infrastructure | pnpm workspace · GitHub Actions · Node.js 24 |

## Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | React 18, Vite, Tailwind CSS, Framer Motion, React Three Fiber, Wouter, Zustand |
| **Blockchain** | Solana Mainnet, Metaplex Bubblegum v5, Jupiter Unified Wallet, cNFT IP-NFT |
| **Backend** | Express 5, PostgreSQL, Drizzle ORM, Pino Logger |
| **Shared** | TypeScript 5.9, OpenAPI Spec, Zod v4, TanStack Query |
| **Infra** | pnpm workspace, Node.js 24, GitHub Actions CI |

## Key Features

| Feature | Description |
|---|---|
| **AI Design Studio** | Describe a therapeutic goal in natural language and receive 6 scored peptide candidates instantly |
| **Evolution Engine** | Mutate any existing sequence through AI-guided point mutations with full scoring |
| **IP-NFT Minting** | Gasless compressed NFT minting on Solana mainnet, platform wallet covers all fees |
| **Community Library** | Browse, filter, and compare all peptides minted across the protocol |
| **Bounty Program** | Post PTMS token rewards for specific research targets; claim by minting qualifying discoveries |
| **Researcher Profiles** | On-chain identity tied to wallet address with full portfolio and contribution history |
| **Peptide Comparison** | Side-by-side comparison of up to 4 peptides with visual score breakdowns |
| **Research Feed** | Live-updated feed of all newly minted IP-NFTs across the protocol |

## Scoring Dimensions

| Metric | Description | Ideal Range |
|---|---|---|
| **Binding Affinity** | Predicted strength of peptide-target interaction | 80 – 100 |
| **Stability** | Structural integrity under physiological conditions | 75 – 100 |
| **Novelty** | Distance from known peptide sequences in literature | 70 – 100 |
| **Toxicity** | Predicted cytotoxicity (lower is better) | 0 – 15 |
| **Evolution Score** | Composite rank across all four metrics | 85 – 100 |

## Cost Per Peptide

| Action | Cost |
|---|---|
| AI Design (~1100 tokens) | ~$0.001 |
| DB Storage (1 row, ~500 bytes) | ~$0.0001 |
| NFT Mint (Solana cNFT via Bubblegum) | ~$0.001 |
| **Total end-to-end** | **~$0.002** |

## Roadmap

| Phase | Milestone |
|---|---|
| Phase 1 | AI Peptide Design Studio · IP-NFT Minting on Solana · Community Feed |
| Phase 2 | PTMS Token Launch · Bounty Program · Peptide Comparison Tool |
| Phase 3 | DAO Governance · Smart Contract Bounty Validation · Reputation System |
| Phase 4 | Partner Protocol Integrations · Cross-chain IP-NFT Bridging · Enterprise API |

## Contributing

All repositories follow the same contribution standards. Before opening a pull request, please read the `CONTRIBUTING.md` in the relevant repo. All submissions must pass CI and include a clear description of the change. Bug reports and feature requests can be filed via the issue templates available in each repository.

<div align="center">

[![Website](https://img.shields.io/badge/peptimus.xyz-00f5ff?style=for-the-badge&logo=googlechrome&logoColor=0a0f1c)](https://peptimus.xyz)
[![App](https://img.shields.io/badge/peptimus.xyz/app-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://peptimus.xyz/app)
[![X](https://img.shields.io/badge/Follow_on_X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/peptimusdev)

**Built by [peptimusdev](https://github.com/peptimusdev)**

</div>
