# 변경 이력

Mossland DAO 거버넌스의 주요 변경사항을 기록합니다.

> *[English Version](CHANGELOG.md)*

## v1.0 (2026.02)

### 거버넌스
- 거버넌스 프로세스를 **Agora**(모스랜드 온체인 거버넌스 플랫폼, 2025년 1월 런칭)로 이전
- 제안, 토론, 투표가 Agora에서 온체인 투명성을 기반으로 진행
- **MAIT**(Mossland DAO AI Toolkit) 통합 — AI 기반 제안 분석 및 드래프팅 지원
- 실험적 프로젝트 섹션 추가: **Algora**(AI 거버넌스 분석), **AO**(Agentic Orchestrator)

### 토큰
- **MOC 네트워크 전환** 반영: Luniverse → Ethereum ERC-20 (2025년 완료)
  - Agora에서 이더리움 마이그레이션 DAO 투표 완료 (2025년 8월)
  - LMT → ERC-20 네트워크 스왑 실행 (2025년 11월)
  - Luniverse MOC 소각 완료 (2025년 12월)
- 거래소 상장 현황 업데이트: Upbit, Bithumb, Coinone, GOPAX

### 리포지토리
- 리포 구조화: `governance/`, `proposals/`, `archive/` 디렉토리 생성
- README.md, README_KR.md 전면 재작성
- Governance v1.0 문서 작성 (EN/KR) — Agora 기반 프로세스 반영
- 업데이트된 MIP 템플릿 작성 — 새 메타데이터 필드 추가 (Agora Proposal ID, On-chain Tx, AI Analysis)
- v0.3 거버넌스 문서를 `archive/v0.3_Governance_2022/`에 아카이브
- MIP 샘플을 `proposals/` 디렉토리로 이동

### 참고사항
- 토론 기간 및 투표 기간은 `[TBD]`로 표기 — Agora 운영 파라미터에 따라 추후 확정
- 거버넌스 v0.3 문서는 역사적 참고를 위해 아카이브에 보존

---

## v0.3 (2022.07)

### 최초 공개
- Mossland DAO 초기 거버넌스 모델 설계
- ApeCoin DAO 거버넌스 모델 기반 (하드 포크)
- Discourse 기반 토론, Snapshot 기반 오프체인 투표
- 9단계 제안 프로세스: Idea → Draft → Analysis → Moderation → Tagging → Review → Live → Final → Implementation
- Luniverse 블록체인의 MOC 토큰
- 공개 파일: `Mossland_DAO_Governance.md`, `MIP_Sample.md`, `Issue.md`
