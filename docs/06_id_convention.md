# ID Convention

## DB Key
고정 DB Key는 `Mxx`, `Cxx`, `Txx`, `Fxx`, `Ixx`, `Sxx`를 사용한다.

## Record ID
Record ID는 DB Key + 연도/연차 + 순번을 기본 패턴으로 사용하되, 기존 Notion에서 확정된 ID가 있으면 이를 우선한다. 기존 Key를 임의 재발급하지 않는다.

## 외부 ID
Notion Page/Data Source ID, GitHub SHA, 공식 시스템 문서번호 등 외부 식별자는 별도 속성으로 보존하며 업무 Key를 대체하지 않는다.

## 변경 금지
참조 중인 Key의 의미 변경·재사용을 금지한다. 폐기 시 Archived 처리하고 새 Key를 발급한다.
