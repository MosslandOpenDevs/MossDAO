# Mossland DAO Governance v1.0

- Date: February 2026
- Version: 1.0
- Purpose: This document defines the governance model for the Mossland DAO, based on the Agora on-chain governance platform.

> *[한국어 버전](Mossland_DAO_Governance_v1_KR.md)*

---

## Overview

Mossland DAO is a decentralized governance framework that manages the Mossland project's ecosystem funds, strategic direction, and community initiatives. This document describes the current governance model (v1.0), which evolved from the initial v0.3 research design (2022) based on community feedback and operational experience.

The v0.3 model was an initial research phase that utilized Discourse for discussion and Snapshot for off-chain voting. To maximize community participation and transparency, Mossland developed **Agora** — a custom on-chain governance platform — enabling direct, verifiable governance on Ethereum.

### Evolution from v0.3 to v1.0

| Aspect | v0.3 (2022) | v1.0 (2026) |
|--------|-------------|-------------|
| Proposal submission | Discourse post | Agora platform |
| Discussion | Discourse (7 days) | Agora forum |
| Voting tool | Snapshot (off-chain) | Agora (on-chain) |
| AI support | None | MAIT proposal analysis & drafting |
| Vote record | Off-chain | On-chain (Ethereum) |
| Token network | Luniverse | Ethereum ERC-20 |

---

## Vision & Core Values

Mossland is building a hyper-connected world bridging the real and virtual — evolving from blockchain and metaverse origins toward Physical AI and agentic systems.

### Core Values

These core values have been carried forward from the founding vision and remain the foundation of Mossland DAO:

- **Transparency**: All processes, decisions, and actions are made public. We communicate genuinely.
- **Challenge and Courage**: We challenge boldly. We are not afraid of new things. We create what has never existed.
- **Top-notch Standards**: We pursue the highest standards.
- **Equality**: All MOC holders are equal.

### Mission

- Continuously developing services spanning blockchain, AI, and Physical AI technologies
- Pursuing a hyper-connected ecosystem with MOC (Mosscoin) as the governance and utility token

---

## Membership

Participation in the Mossland DAO — including submitting proposals, joining discussions, and voting — is restricted to Mossland DAO Members.

**How to become a member:**
- Hold MOC (Mosscoin), an Ethereum ERC-20 token
- Connect your wallet (e.g., MetaMask) on [Agora](https://agora.moss.land/) to verify membership

Holding MOC grants DAO membership. 1 MOC = 1 vote.

---

## Governance Platform: Agora

Agora is Mossland's on-chain governance platform, launched in January 2025.

- **Proposal submission**: Members submit proposals directly on Agora
- **Community discussion**: Open forum for deliberation and feedback
- **On-chain voting**: Transparent, verifiable votes recorded on Ethereum
- **Results and execution**: Voting outcomes are publicly recorded on-chain

| | |
|---|---|
| Platform | [agora.moss.land](https://agora.moss.land/) |
| Source | [github.com/MosslandOpenDevs/Agora](https://github.com/MosslandOpenDevs/Agora) |

---

## Proposal Categories

MIPs (Mossland Improvement Proposals) fall into three main categories, consistent with the v0.3 framework:

### Core
Proposals related to ecosystem fund allocation and brand decisions.
- **Ecosystem Fund Allocation**: Proposals on how DAO funds should be utilized
- **Brand Decision**: Proposals for brands, projects, and collaborations created by the DAO

### Process
Proposals to change a process or implementation — including procedures, guidelines, decision-making processes, and changes to DAO tools or environments.

### Informational
General guidance or information for the community.

> Resubmitted proposals must be classified with a "(Resubmission)" tag in all categories.

---

## Proposal Process (Agora-based)

### Step 1: Proposal Submission
Authors submit a proposal on the Agora platform using the [MIP Template](../proposals/MIP_Template.md). Multiple members may co-author a proposal. The proposal must comply with DAO guidelines.

### Step 2: Community Discussion
The proposal enters a community discussion period on the Agora forum. Members can provide feedback, ask questions, and suggest revisions. Authors may respond to feedback but should not modify the original proposal text during this period.

> Discussion period: `[TBD]`

### Step 3: Proposal Review
Moderators and administrators review the proposal for compliance with DAO-approved guidelines. The review covers:
- Adherence to proposal template requirements
- Clarity of implementation costs and timeline
- Absence of prohibited content (illegal activity, hate speech, pornography, or conflict with Mossland Foundation's mission and values)

### Step 4: On-chain Vote
Approved proposals proceed to on-chain voting on Agora.

- **Voting power**: 1 MOC = 1 vote (fractional tokens are rounded down)
- **Voting options**: "In Favor" or "Against"

> Voting period: `[TBD]`

### Step 5: Resolution
- **Accepted**: Proposals that receive a majority "In Favor" vote proceed to implementation
- **Rejected**: Authors may resubmit using the resubmission process
- **Stalled**: Proposals that receive no votes or are tied may be resubmitted

### Step 6: Implementation
Accepted proposals are implemented based on the specifications in the MIP. The Mossland Foundation's Project Management Team is responsible for supporting implementation but not for executing it directly.

---

## AI-Augmented Governance

### MAIT (Mossland DAO AI Toolkit)

MAIT integrates AI capabilities into the governance process:

- **Proposal analysis**: AI-powered analysis of proposal content, feasibility, and potential impact
- **Drafting assistance**: Helps authors structure and refine proposals before submission
- **Voting data insights**: Real-time analytics on community voting patterns and participation

| | |
|---|---|
| Platform | [mait.moss.land](https://mait.moss.land/) |

### Experimental Projects

> The following are in **experimental** stages. Features and availability may change.

- **Algora**: AI governance analytics platform for analyzing DAO activity and trends ([GitHub](https://github.com/MosslandOpenDevs/Algora))
- **AO (Agentic Orchestrator)**: AI agent orchestration for automated governance workflows ([GitHub](https://github.com/MosslandOpenDevs/agentic-orchestrator))

---

## Voting Mechanism

Mossland DAO's consensus mechanism ensures voting is fair, transparent, and accessible.

- **Platform**: Agora (on-chain, Ethereum)
- **Voting power**: 1 MOC = 1 vote
- **Rounding**: Fractional tokens are rounded down (e.g., 100.9 MOC = 100 votes)
- **Options**: "In Favor" and "Against"
- **Threshold**: Majority "In Favor" = accepted

---

## Proposal Conflict Rules

These rules are carried forward from the v0.3 framework:

1. If a proposed MIP conflicts with a proposal currently being voted on, the second proposal will not go to vote until a decision has been made on the first proposal.
2. Proposals that directly conflict with an approved proposal cannot be submitted for vote within 3 months after the original proposal's implementation.

---

## DAO Board

The Mossland DAO BOARD manages DAO proposals and serves the vision of the community.

- A DAO-wide vote is held annually to determine BOARD members
- BOARD members serve 12-month terms
- BOARD members may be removed and replaced before the end of their term by a majority vote of MOC holders
- The BOARD reviews proposals tagged for administrative review and may return, approve, or request changes

---

## MOC Network Migration History

| Date | Event |
|------|-------|
| 2022 | MOC operated on Luniverse blockchain |
| 2025 Aug | DAO vote on Agora approved Ethereum mainnet migration |
| 2025 Nov | MOC LMT → ERC-20 network swap executed |
| 2025 Dec | Luniverse MOC burn completed |

MOC is now exclusively an Ethereum ERC-20 token. The Luniverse-based MOC has been fully burned.

---

## General Guidelines

1. For a proposal to go to vote, the total cost of implementation must be clear.
2. DAO members should search past proposals to ensure their idea has not already been submitted.
3. Proposals containing illegal activity, hate speech, pornography, or conflict with the Mossland Foundation's mission or values will not be accepted for voting.
4. The total implementation cost must be transparent and calculable.

---

## Appendix: Governance Evolution History

| Version | Date | Description |
|---------|------|-------------|
| v0.3 | July 2022 | Initial governance model design. Discourse/Snapshot-based. ApeCoin DAO reference. See [archive](../archive/v0.3_Governance_2022/). |
| v1.0 | February 2026 | Agora-based on-chain governance. MAIT AI augmentation. MOC ERC-20 on Ethereum. Repository restructured. |
