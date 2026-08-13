# Database Inventory

| Key | Database | Layer | Primary role |
|---|---|---|---|
| M01 | WBS | Master | 업무분류 기준 |
| M02 | People | Master | 인력 기준 |
| M03 | Org | Master | 조직 기준 |
| M04 | KPI | Master | 성과지표 정의 |
| M05 | Students | Master | 학생 기준 / Restricted |
| M06 | Companies | Master | 참여기업 기준 |
| M07 | Education Catalog | Master | 교육과정 기준 |
| C01 | Projects | Core | 사업/프로젝트 |
| C02 | Work Packages | Core | WP |
| C03 | Tasks | Core | 과업 |
| C04 | Deliverables | Core | 산출물 |
| C05 | Evidence | Core | 증빙 Index |
| C06 | Meetings | Core | 회의 |
| C07 | Decisions | Core | 의사결정 |
| C08 | Issues | Core | 리스크/이슈/Source Conflict |
| T01 | Participation | Transaction | 학생 참여/이수 |
| T02 | Career Outcomes | Transaction | 취·창업/진로 |
| T03 | Company Participation | Transaction | 기업 참여실적 |
| F01 | Budget Allocation | Finance | 편성/배정 |
| F02 | Budget Execution | Finance | 실제 집행 |
| I01 | KPI Performance | Integration | KPI 실적 |
| I02 | KPI Evidence | Integration | KPI-증빙 연결 |
| S01 | Templates | Support | 운영 템플릿 |
| S02 | Automation Logs | Support | 자동화 실행 기록 |

## Migration 현재 상태
C01 11, C02 11, C03 10, C05 7, C06 1, C07 1, C08 신규 3, F01 14건이 Core Wave 1에서 이관되었다. M07은 정합 확인 9건만 이관되었다. M06/M05/T01/T02/F02는 Gate 조건에 따라 보류 또는 제한된다.
