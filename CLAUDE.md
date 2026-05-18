---
id: claude-md-project
date: YYYY-MM-DD
tags: [process, documentation]
---

# 기록 규칙 (PROJECT_NAME)

> ⚠️ 이 파일은 **기록/운영 전용**입니다. 코딩/디자인 규칙은 `.cursorrules`를 참조하세요.  ← v2 NEW (패치 #5: 파일 분업 명시)
> See also: `AGENTS.md` for top-level project rules (if exists)  ← v2 NEW (패치 #3: AGENTS.md 참조)

## 현재 상태  ← v2 NEW (패치 #2: 현재 상태 섹션)
- **Phase:** __FILL__ (예: Phase 1 — MVP)
- **블로커:** 없음
- **다음 액션:** __FILL__
- **마지막 업데이트:** YYYY-MM-DD

## ADR (Architecture Decision Record)
- 새로운 기술/라이브러리/API/DB를 선택하거나 변경할 때,
  docs/adr/ 에 ADR 파일을 자동 생성하라.
- 파일명: ADR-{번호}-{제목}.md
- 포맷:
  ---
  id: ADR-{번호}
  date: YYYY-MM-DD
  status: proposed | accepted | deprecated | superseded
  tags: [기술영역]
  ---
  **맥락 (Context)**
  **결정 (Decision)**
  **대안 (Alternatives)**
  **결과 (Consequences)**

## 작업 로그
- 세션 종료 또는 주요 기능 완성 시, docs/log/ 에 작업 로그를 남겨라.
- 파일명: YYYY-MM-DD-{작업명}.md

## 트러블슈팅 로그
- 에러 해결 완료 시, docs/troubleshooting/ 에 기록하라.
- 파일명: TS-{번호}-{증상 요약}.md
- 포맷: 증상 → 원인 → 해결 → 교훈

## TIL
- 코딩 중 새로 알게 된 개념이 있으면 docs/til.md 에 한 줄 추가.
- 포맷: `- [YYYY-MM-DD] 내용`

## 스키마/API 변경 이력
- DB 테이블이나 API 엔드포인트 변경 시 docs/changelog.md 에 기록.

## /done 커맨드  ← v2 NEW (패치 #1: /done 커맨드)
세션 종료 시 `/done` 을 입력하면 아래 포맷으로 자동 요약을 생성하라:

### 세션 요약 (YYYY-MM-DD)

**작업 요약:** (완료한 작업 1~3줄)

**결정 사항:** (이번 세션에서 내린 기술/설계 결정)

**다음 할 일:** (다음 세션에서 이어할 작업)

**블로커:** (막힌 것, 없으면 "없음")

- 요약 생성 후 docs/log/ 에 자동 저장하고, 위 "현재 상태" 섹션을 업데이트하라.

## 작업 종료 전 체크리스트
- 작업 종료 전 반드시:
  1) ADR 빠진 거 없는지
  2) 작업 로그 작성
  3) 에러 있었으면 트러블슈팅 로그
  4) 새로 배운 거 있으면 TIL
  5) `/done` 으로 세션 요약 생성  ← v2 NEW
