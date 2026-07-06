# 변경 이력

Mossland DAO 거버넌스의 주요 변경사항을 기록합니다.

> *[English Version](CHANGELOG.md)*

## v1.2 (2026.07)

### 문서
- README(EN/KR)와 Governance v1.0 문서(EN/KR) 전반에서 **Agora 투표 용어 정정**: Agora 투표는 **가스리스·오프체인**(Snapshot 방식)으로 진행됩니다 — MOC 보유자는 EIP-712 서명 한 번으로 찬성/반대/기권을 제출하며(트랜잭션·가스 없음), 투표 가중치는 스냅샷 블록 시점의 MOC 잔액으로 산정됩니다. 투표는 이더리움에 트랜잭션으로 기록되는 대신 암호학적으로 서명되어 공개 검증이 가능합니다. 기존의 "온체인 투표 / 이더리움에 기록" 표현은 부정확했습니다.
- Agora를 Mossland DAO의 **공개 의사결정 플랫폼**으로 재정의 (기존 "온체인 거버넌스 플랫폼")
- 실험적 "Labs" 프로젝트(Algora, AO)는 **거버넌스 효력이 없음**을 명확화 — 구속력을 갖는 것은 Agora에서의 사람 MOC 보유자 투표뿐
- MIP 메타데이터 필드명 변경: **온체인 Tx 참조 → 결과 검증 참조** (EN/KR 템플릿)

### 참고사항
- 거버넌스 모델(제안 프로세스, 투표 규칙, 멤버십)은 **변경 없음** — 이번 릴리스는 플랫폼/메커니즘 설명만 정정
- MOC 토큰 자체는 이더리움 ERC-20 자산으로 유지됨 — Agora *투표*에 대한 설명만 정정됨

---

## v1.1 (2026.07)

### 플랫폼
- **Agora 업데이트**: **MAIT**(Mossland DAO AI Toolkit)를 Agora에 내장 AI 레이어로 직접 통합 — 더 이상 독립 서비스가 아님 (`mait.moss.land` 종료)
- **Mossland Passport** 런칭 (베타 / 스텔스 소프트 런칭) — MOC 홀더를 위한 셀프커스터디 지갑 활성화 프로그램: 가스리스 서명 인증, 거버넌스 위임 및 시그널 투표, 월간 체크인 스탬프, 셀프커스터디 출금 수수료 보상, "Founding 2026" 기념 스탬프 ([passport.moss.land](https://passport.moss.land/))

### 문서
- MAIT를 Agora의 내장 AI 기능으로 재정의 (MAIT 명칭은 유지); README 및 거버넌스 문서 전반에서 독립 `mait.moss.land` 플랫폼 링크 제거
- README(EN/KR)와 Governance v1.0 문서(EN/KR)에 **Mossland Passport (Beta)** 섹션 추가
- 링크 표 업데이트: MAIT 제거, Passport 추가
- Agora 기능 목록에 AI 지원 항목 추가
- **Algora**·**AO** 설명을 현행 범위에 맞게 갱신하고 라이브 URL 추가 ([algora.moss.land](https://algora.moss.land/), [ao.moss.land](https://ao.moss.land/))

### 참고사항
- 거버넌스 모델(제안 프로세스, 투표 규칙, 멤버십)은 v1.0에서 **변경 없음** — 이번 릴리스는 플랫폼/툴링 설명만 업데이트
- Mossland Passport는 베타(스텔스 소프트 런칭) 단계로 기능과 가용성이 변경될 수 있으며, Passport를 통한 시그널 투표와 위임은 참여 시그널로서 Agora의 공식 MOC 가중 투표를 대체하지 않음

---

## v1.0 (2026.02)

### 거버넌스
- 거버넌스 프로세스를 **Agora**(Mossland DAO의 공개 의사결정 플랫폼, 2025년 1월 런칭)로 이전
- 제안, 토론, 가스리스 오프체인(EIP-712) 투표가 Agora에서 공개 검증 가능한 방식으로 진행
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
