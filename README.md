# BootCamp PM — Baseline v1.0

국립한국교통대학교 첨단산업 인재양성 부트캠프(AI)사업단 PM 시스템의 기술 기준 저장소입니다.

## 목적
- Notion PM의 구조·키·관계·수식·상태·Migration 규칙을 버전 관리합니다.
- Notion은 운영 UI/협업·일정·요약 계층으로 사용하고, GitHub는 설계·변경이력·기술자산의 기준 저장소로 사용합니다.
- RCMS, K-PASS, 대학 전자결재, 학사·회계·자산 시스템 및 공식 문서 원본을 대체하지 않습니다.

## Baseline
- System: `BootCamp-PM-v1.0`
- Phase 0~6: 완료
- Phase 7: `Core Migration Complete / Deferred Verification Items`
- Phase 8: GitHub 기술자산 기준선 구축

## 핵심 원칙
1. Source of Truth와 운영 UI를 분리합니다.
2. Legacy 원본은 삭제·덮어쓰기하지 않습니다.
3. 불일치 값은 추정·보정하지 않고 Source Conflict로 유지합니다.
4. L4/Restricted 개인정보, 계좌·주민등록번호·토큰·비밀번호·비공개 평가자료는 저장하지 않습니다.
5. 완료·승인·제출·집행 상태는 공식 근거 확인 후 갱신합니다.

## 문서 구성
- `docs/01_architecture.md`
- `docs/02_database_inventory.md`
- `docs/03_data_dictionary.md`
- `docs/04_relation_map.md`
- `docs/05_formula_rollup_rules.md`
- `docs/06_id_convention.md`
- `docs/07_status_dictionary.md`
- `docs/08_confidentiality_model.md`
- `docs/09_kpi_source_mapping.md`
- `docs/10_evidence_gate.md`
- `docs/11_migration_policy.md`
- `docs/12_deferred_gates.md`
- `docs/13_template_specification.md`
- `docs/14_dashboard_specification.md`
- `CHANGELOG.md`

## 현재 Deferred Gate
- M06 참여기업 44/45 Source Conflict
- M07 추가 고급과정 1건 공식 운영대상 여부 미확정
- 연구활동비 498/565백만원 Source Conflict
- M05/T01/T02 L4 Compliance Gate
- F02 실제집행 RCMS·원인행위·증빙 대조 미완료

## 변경관리
Baseline 변경은 근거·영향범위·검증결과를 남기고 `CHANGELOG.md`에 기록합니다. 구조 변경은 임의 재설계가 아니라 승인된 변경으로만 수행합니다.
