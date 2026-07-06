# Changelog

All notable changes to the Mossland DAO governance will be documented in this file.

> *[한국어 버전](CHANGELOG_KR.md)*

## v1.3 (2026.07)

### Governance
- **Agora vote weighting is now delegation-aware**: each vote's weight is the voter's **delegated MOC voting power** at the proposal's snapshot block (`ERC20Votes` — `getPastVotes`), with a **raw-balance fallback** (`balanceOf`) for holders who have never delegated. 1 MOC = 1 vote still applies — a voter's weight comes from their delegated MOC voting power, or their raw balance if they have never delegated.

### Documentation
- Updated README (EN/KR) and the Governance v1.0 document (EN/KR) to describe Agora's **delegated MOC voting power** weighting with a raw-balance fallback (previously described as weighting by raw MOC balance)
- Separated Passport's two participation mechanisms, correcting an earlier bundling: **signal votes** are non-binding sentiment signals that do **not** replace the Agora vote, whereas **delegation** via Passport now **flows into** the formal MOC-weighted Agora vote

### Notes
- The governance model (proposal process, voting rules, membership) is **unchanged**; this release reflects Agora's delegation-aware vote weighting and refines the related Passport wording
- Voter guidance: to vote with your MOC, no action is required — your balance counts directly (raw-balance fallback); if you delegate, your delegate carries your weight; self-delegate to retain your own voting power

---

## v1.2 (2026.07)

### Documentation
- **Corrected Agora voting terminology** across README (EN/KR) and the Governance v1.0 document (EN/KR): Agora voting is **gasless and off-chain** (Snapshot-style) — MOC holders cast For / Against / Abstain with a single EIP-712 wallet signature (no transaction, no gas), and vote weight is derived from each voter's MOC balance at a snapshot block. Votes are cryptographically signed and publicly verifiable rather than written to Ethereum as transactions. The earlier "on-chain voting / recorded on Ethereum" wording was inaccurate.
- Reframed Agora as Mossland DAO's **public decision platform** (previously described as an "on-chain governance platform")
- Clarified that experimental "Labs" projects (Algora, AO) carry **no governance authority** — only human MOC-holder votes on Agora are binding
- Renamed the MIP metadata field **On-chain Tx Reference → Result Verification Reference** (EN/KR templates)

### Notes
- The governance model (proposal process, voting rules, membership) is **unchanged**; this release corrects platform/mechanism descriptions only
- The MOC token itself remains an Ethereum ERC-20 asset; only the characterization of Agora *voting* was corrected

---

## v1.1 (2026.07)

### Platform
- **Agora update**: **MAIT** (Mossland DAO AI Toolkit) is now integrated directly into Agora as a built-in AI layer — no longer a standalone service (`mait.moss.land` retired)
- Launched **Mossland Passport** (beta / stealth soft launch) — a self-custody wallet activation program for MOC holders: gas-free signature authentication, governance delegation & signal voting, monthly check-in stamps, self-custody withdrawal fee compensation, and a "Founding 2026" commemorative stamp ([passport.moss.land](https://passport.moss.land/))

### Documentation
- Reframed MAIT as Agora's built-in AI feature (kept the MAIT name); removed the standalone `mait.moss.land` platform link across README and Governance docs
- Added **Mossland Passport (Beta)** section to README (EN/KR) and the Governance v1.0 document (EN/KR)
- Updated Links tables: removed MAIT, added Passport
- Added AI-assistance note to the Agora feature lists
- Refreshed **Algora** and **AO** descriptions to their current scope and added live URLs ([algora.moss.land](https://algora.moss.land/), [ao.moss.land](https://ao.moss.land/))

### Notes
- The governance model (proposal process, voting rules, membership) is **unchanged** from v1.0; this release updates platform/tooling descriptions only
- Mossland Passport is in beta (stealth soft launch) — features and availability may change; signal votes and delegation via Passport are participation signals and do not replace the formal MOC-weighted vote on Agora

---

## v1.0 (2026.02)

### Governance
- Migrated governance process to **Agora**, Mossland DAO's public decision platform (launched January 2025)
- Proposals, discussions, and gasless off-chain (EIP-712) votes are now conducted on Agora with public verifiability
- Integrated **MAIT** (Mossland DAO AI Toolkit) for AI-augmented proposal analysis and drafting
- Added experimental projects section: **Algora** (AI governance analytics) and **AO** (Agentic Orchestrator)

### Token
- Reflected **MOC network migration** from Luniverse to Ethereum ERC-20 (completed 2025)
  - DAO vote on Agora approved migration (August 2025)
  - LMT → ERC-20 swap executed (November 2025)
  - Luniverse MOC burn completed (December 2025)
- Updated exchange listings: Upbit, Bithumb, Coinone, GOPAX

### Repository
- Restructured repository: `governance/`, `proposals/`, `archive/` directories
- Rewrote README.md and README_KR.md to reflect current state
- Created Governance v1.0 document (EN/KR) with Agora-based process
- Created updated MIP Template with new metadata fields (Agora Proposal ID, On-chain Tx, AI Analysis)
- Archived v0.3 governance documents in `archive/v0.3_Governance_2022/`
- Moved MIP samples to `proposals/` directory

### Notes
- Discussion and voting periods marked as `[TBD]` — to be finalized based on Agora operational parameters
- Governance v0.3 documents preserved in archive for historical reference

---

## v0.3 (2022.07)

### Initial Release
- Initial governance model design for Mossland DAO
- Based on ApeCoin DAO governance model (hard fork)
- Discourse-based discussion and Snapshot-based off-chain voting
- 9-step proposal process: Idea → Draft → Analysis → Moderation → Tagging → Review → Live → Final → Implementation
- MOC token on Luniverse blockchain
- Published: `Mossland_DAO_Governance.md`, `MIP_Sample.md`, `Issue.md`
