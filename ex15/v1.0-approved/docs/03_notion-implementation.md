# Notion 구현 명세

## 신규 객체
- EX-15: 단계 루트
- GH15: 승인 저장대상·검증 기록
- EX15-UI01: 사용자 검토 화면
- EX15-SEC: 보안 체크
- EX15-MAN: 수동 절차
- EX15-RPT: 결과보고와 승인 Gate

## GH15
- Native Unique ID Prefix: GH15
- 공통 속성: CF01~CF19
- 단계 속성: GS01~GS16
- Template: L1 설계문서, 허용 원문 사전검사, 저장 차단, 롤백
- View: 9종
- 합성자료: 12건, 검증 후 전량 보관 및 공식값 제외

기존 Notion 페이지·DB·UI-21·S01은 조회 외 변경하지 않는다.
