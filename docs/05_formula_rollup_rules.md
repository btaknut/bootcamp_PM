# Formula & Rollup Rules

## 원칙
- 계산 가능한 값은 중복 입력하지 않고 Formula/Rollup으로 산출한다.
- Formula는 Canonical Relation을 전제로 한다.
- 합계가 원천과 불일치하면 Formula를 맞추기 위해 원천을 수정하지 않는다.

## Budget
F01 편성액은 Allocation 원천값이다. F02 집행액은 공식 집행 근거가 있는 Transaction만 생성한다. 집행률은 `Execution / Allocation`으로 산출하며 Allocation=0인 경우 별도 예외 처리한다.

## KPI
달성률은 KPI별 정의된 산식과 기준 단위를 따른다. 기준값·연차목표·실적을 혼동하지 않는다. Evidence Gate를 통과하지 않은 실적은 공식 달성으로 확정하지 않는다.

## Dashboard
Archived/Pilot 합성 레코드는 운영 Dashboard 집계에서 제외한다. Filter와 Rollup은 동일 제외규칙을 적용한다.
