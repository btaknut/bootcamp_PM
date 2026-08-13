# Relation Map

## 업무 계층
M01 WBS → C01 Project → C02 Work Package → C03 Task → C04 Deliverable → C05 Evidence.

## 의사결정 계층
C06 Meeting → C07 Decision → C03 Task/C08 Issue.

## 성과 계층
M04 KPI → I01 KPI Performance → I02 KPI Evidence → C05 Evidence.

## 교육/참여 계층
M07 Education Catalog → T01 Participation → M05 Students. 기업 참여는 M06 Companies → T03 Company Participation → 교육/프로젝트/성과 객체와 연결한다.

## 재무 계층
C01/C02/C03 → F01 Budget Allocation → F02 Budget Execution → C05 Evidence.

## Canonical 원칙
- 관계는 단일 Owner가 관리한다.
- 복수 Project가 걸린 Legacy Task는 Canonical Project 1개를 선택하고 보조 관계는 Notes로 보존한다.
- Dashboard는 Relation/Rollup 결과를 소비하며 원천을 복제하지 않는다.
