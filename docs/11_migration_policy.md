# Migration Policy

## 방식
Copy → Normalize → Validate → Activate. Legacy 원본은 보존한다.

## Wave 1
비민감 Core를 우선 이관한다. 공란/무효 행은 제외하고 제외사유를 기록한다.

## 정규화
Legacy에 WP가 없으면 Project별 `Legacy 운영업무 이관` WP를 생성한다. 복수 Project Task는 Canonical Project 1개를 선택한다.

## Conflict
Company/Education/KPI/Budget 등 Source Conflict 값은 확정값으로 잠그지 않는다.

## Restricted
L4 데이터는 Compliance와 권한 Gate 전 이관하지 않는다.

## Archive
Migration 검증 완료 후 Legacy Hub를 Read-only Archive로 전환할 수 있으나 삭제는 별도 승인 없이는 수행하지 않는다.
