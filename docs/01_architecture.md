# Architecture — BootCamp-PM-v1.0

## 계층
- Master: M01~M07
- Core: C01~C08
- Transaction: T01~T03
- Finance: F01~F02
- Integration: I01~I02
- Support: S01~S02

## 24 DB Baseline
M01 WBS, M02 People, M03 Org, M04 KPI, M05 Students, M06 Companies, M07 Education Catalog, C01 Projects, C02 Work Packages, C03 Tasks, C04 Deliverables, C05 Evidence, C06 Meetings, C07 Decisions, C08 Issues, T01 Participation, T02 Career Outcomes, T03 Company Participation, F01 Budget Allocation, F02 Budget Execution, I01 KPI Performance, I02 KPI Evidence, S01 Templates, S02 Automation Logs.

## SoT 원칙
공식시스템/공식문서 > 승인된 Master/Core > Transaction > Dashboard/요약. Notion은 외부 공식시스템을 대체하지 않는다.

## Relation Owner
관계는 Canonical Owner 한 곳에서 정의하고 역방향은 Rollup/Relation으로 소비한다. 중복 입력을 금지한다.

## 변경 원칙
Legacy DB 수정 없이 Baseline v1.0 영역에서 확장한다. 구조 변경은 영향분석과 검증 후 승인된 변경으로 수행한다.
