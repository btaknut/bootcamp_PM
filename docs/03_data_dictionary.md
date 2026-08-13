# Data Dictionary — Baseline Rules

이 문서는 속성별 상세 사전의 상위 규칙이다. Notion 실제 Schema가 최종 참조이며 GitHub 문서는 변경통제용 Snapshot이다.

## 공통 필드군
- ID/Key: DB별 고유 식별자
- Name/Title: 사람이 읽는 명칭
- Status/Data Status: 운영 상태와 데이터 상태를 분리
- Owner: Canonical 책임자
- Project/WP: 업무 계층 Relation
- Source/Evidence: 원천 및 근거
- Confidentiality: 공개등급
- Created/Updated: 변경 추적

## 데이터 상태
- Active: 운영 사용 가능
- Draft: 미확정
- Hold: Gate 미해소
- Conflict: 원천 불일치
- Archived: 운영 조회 제외

## Null 원칙
미확정 값을 임의 보간하지 않는다. Null은 오류가 아니라 '미확정/미수집' 상태일 수 있으며 필요 시 C08 Issue로 관리한다.

## 공식값 원칙
숫자·상태·명단은 공식 문서/시스템 대조 전 Verified로 승격하지 않는다.
