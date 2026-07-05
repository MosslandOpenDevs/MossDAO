# Mossland DAO

> *[한국어 버전](README_KR.md)*

## Mossland Vision

Mossland is building a hyper-connected world that bridges the real and virtual — from blockchain and metaverse origins to Physical AI and agentic systems. Our goal is to realize this hyper-connected technology and contribute to human society through the pursuit of our core values and mission.

## What is the Mossland DAO?

Mossland DAO is a community-driven decentralized governance framework that manages the Mossland project's ecosystem, funds, and strategic direction. MOC (Mosscoin) holders are members of the DAO and participate in proposals, discussions, and on-chain voting to shape the future of Mossland.

- [Mossland DAO Governance v1.0](governance/Mossland_DAO_Governance_v1.md)

## Governance Platform: Agora

**Agora** is Mossland's on-chain governance platform, launched in January 2025. It was built to maximize community participation and transparency in the governance process.

- **On-chain voting** — Transparent, verifiable governance decisions recorded on Ethereum
- **Proposal submission** — Any MOC holder can submit proposals through Agora
- **Community discussion** — Open forum for deliberation before voting
- **Built-in AI assistance** — AI proposal drafting and governance briefs, folded in from the former MAIT toolkit (see below)
- **Advanced search & filter** — Search proposals by status, category, and date; CSV export for analysis
- **Mobile-optimized** — Responsive design for full participation on any device
- **Collaborative decision-making** — 1 MOC = 1 vote

| | |
|---|---|
| Platform | [agora.moss.land](https://agora.moss.land/) |
| Source | [github.com/MosslandOpenDevs/Agora](https://github.com/MosslandOpenDevs/Agora) |

## AI-Augmented Governance

Agora has a built-in AI layer — the capabilities of the former **MAIT (Mossland DAO AI Toolkit)**, now folded directly into Agora. The standalone MAIT service has been retired (`mait.moss.land` redirects to Agora).

- **AI proposal drafting** — generate proposal and topic drafts while writing (powered by Google Gemini)
- **AI governance briefs** — neutral, extractive summaries of proposals, bound to each proposal's content hash (powered by Claude)

> There is no separate MAIT app or login — these features live inside [agora.moss.land](https://agora.moss.land/).

## Mossland Passport (Beta)

**Mossland Passport** is a self-custody wallet activation program for MOC holders, currently in **beta**. It lets holders prove MOC ownership and participate in governance directly from a self-custodial wallet — with no gas fees and without ever exposing private keys or seed phrases.

- **Gas-free signature authentication** — Verify MOC ownership by signing a message; no on-chain transaction or fee required
- **Governance delegation & signal voting** — Delegate voting power and cast signal votes on community sentiment
- **Monthly check-in stamps** — Track ongoing participation with monthly on-record check-ins
- **Withdrawal fee compensation** — Support for moving MOC from exchanges to self-custody
- **Founding 2026 stamp** — A commemorative stamp for early participants
- **Transparent by design** — Signature records and activity are publicly disclosed

> 🔒 Mossland Passport never requests private keys or seed phrases.
>
> 📋 Signal votes and delegation via Passport are participation signals — they do not replace binding on-chain votes on Agora.

| | |
|---|---|
| Platform | [passport.moss.land](https://passport.moss.land/) |
| Status | Beta (soft launch) |

## Experimental Projects

> The following projects are in **experimental** stages. Features and availability may change.

- **Algora** — A 24/7 "agentic governance" platform where 30+ AI agent personas continuously debate DAO topics and surface recommendations for human decision-makers ([algora.moss.land](https://algora.moss.land/) · [GitHub](https://github.com/MosslandOpenDevs/Algora))
- **AO (Agentic Orchestrator)** — A multi-agent orchestration engine that runs a swarm of AI agents through a divergence → convergence → planning cycle to propose and build software from live signals ([ao.moss.land](https://ao.moss.land/) · [GitHub](https://github.com/MosslandOpenDevs/agentic-orchestrator))

## MOC Token & Membership

**MOC (Mosscoin)** is an Ethereum ERC-20 token. The network migration from Luniverse to Ethereum was completed in 2025, approved through a DAO vote on Agora.

- Holding MOC = Mossland DAO membership
- 1 MOC = 1 vote
- Connect your wallet (e.g., MetaMask) on Agora to participate

**Listed Exchanges**: Upbit, Bithumb, Coinone, GOPAX

## MIP (Mossland Improvement Proposal)

MIPs are the formal mechanism for proposing changes to the Mossland ecosystem. The process follows these stages:

1. **Proposal Submission** — Submit via Agora
2. **Community Discussion** — Open discussion on Agora forum
3. **Review** — Moderator/admin review
4. **On-chain Vote** — 1 MOC = 1 vote
5. **Resolution** — Majority approval = accepted
6. **Implementation**

- [MIP Template](proposals/MIP_Template.md)
- [MIP Sample (MIP-1)](proposals/MIP_Sample.md)
- [Governance v1.0 Document](governance/Mossland_DAO_Governance_v1.md) — Full process details

## Links

| Resource | URL |
|----------|-----|
| Mossland Website | [moss.land](https://www.moss.land/) |
| Disclosure | [disclosure.moss.land](https://disclosure.moss.land/) |
| Agora (Governance) | [agora.moss.land](https://agora.moss.land/) |
| Passport (Beta) | [passport.moss.land](https://passport.moss.land/) |
| GitHub (Mossland) | [github.com/mossland](https://github.com/mossland) |
| GitHub (MosslandOpenDevs) | [github.com/MosslandOpenDevs](https://github.com/MosslandOpenDevs) |
| X (Twitter) | [@theMossland](https://twitter.com/theMossland) |

## Archive

The previous governance model (v0.3, 2022) based on Discourse and Snapshot is preserved in [`archive/v0.3_Governance_2022/`](archive/v0.3_Governance_2022/).

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for the history of governance updates.
