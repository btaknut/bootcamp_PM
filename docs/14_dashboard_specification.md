# Dashboard Specification

Phase 6에서 확정한 3계층 Dashboard를 기준으로 한다.

## Executive
목표 달성, 고위험 이슈, 예산, 주요 의사결정 중심.

## PM
Project/WP/Task, KPI 경보, Budget/Evidence Gate, 마감·Blocker 중심.

## Practitioner
담당 Task, 일정, 제출물, Evidence, 회의 후속조치 중심.

## 공통 규칙
- Canonical DB의 Linked View를 사용한다.
- 동일 값을 Dashboard에 복제하지 않는다.
- Archived/Pilot 합성 Record는 운영 집계에서 제외한다.
- Filter/Chart/Table/Board/Calendar의 집계 정의를 문서화한다.
- 공식값 미검증 상태는 시각적으로 Verified 값과 구분한다.
