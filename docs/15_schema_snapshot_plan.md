# Phase 8.5 — Notion Schema Snapshot Plan

## 목적
Phase 8 GitHub Baseline 문서와 실제 Notion Baseline v1.0의 24개 DB 구조를 1:1로 대조·고정한다.

## Snapshot 필드
각 DB마다 다음 항목을 기록한다.

- DB Key
- Notion Database/Data Source ID
- Title
- Layer
- Source of Truth 역할
- Property Name
- Property Type
- Required 여부
- ID/Unique 규칙
- Relation Target
- Canonical Relation Owner
- Rollup Source / Function
- Formula Expression / 계산 의미
- Status/Select Dictionary
- Confidentiality Level
- Migration Status
- Deferred Gate 여부
- 검증일

## 24 DB 대상
### Master
M01 WBS, M02 KPI, M03 Evidence Type, M04 Budget Category, M05 People/Student, M06 Companies, M07 Education Catalog

### Core
C01 Projects, C02 Work Packages, C03 Tasks, C04 Deliverables, C05 Evidence, C06 Meetings, C07 Decisions, C08 Issues

### Transaction
T01 Enrollment/Participation, T02 Career/Outcome, T03 Company Participation

### Finance
F01 Budget Allocation, F02 Budget Execution

### Integration/Support
I01 External System Registry, S01 Resource Registry, S02 Change/Validation Log

## 우선 검증 순서
1. C08 Issues — Deferred Gate 보존 여부
2. F01 Budget Allocation — 14건/1,425백만원 구조 및 상태
3. M07 Education Catalog — 9건 이관/추가 고급 1건 Hold 분리 여부
4. C01/C02/C03 — Project/WP/Task Canonical Chain
5. C05/C06/C07 — Evidence/Meeting/Decision 관계
6. M06/T01/T02/F02 — Gate 상태 확인
7. 나머지 Master/Support/Integration

## 완료 조건
- 24개 DB 모두 실제 Notion ID와 Schema가 기록됨
- GitHub Data Dictionary와 불일치 항목 0건 또는 승인된 Exception으로 분류됨
- Deferred Gate가 일반 데이터와 혼합되지 않음
- Formula/Rollup/Relation의 Canonical Owner가 문서와 일치함
- L4/Restricted 정보가 GitHub에 포함되지 않음

## 현재 상태
`BLOCKED — Notion connector temporarily unavailable for live schema retrieval.`

Notion 접근이 복구되면 이 문서를 체크리스트로 사용하여 Phase 8.5를 즉시 재개한다.
