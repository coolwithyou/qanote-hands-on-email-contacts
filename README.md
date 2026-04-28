# QA Note Hands-on: 이메일 연락처

QA Note 핸즈온 세션용 정적 HTML 테스트 사이트입니다.

## 세션 목표

참가자는 Vercel로 배포된 이 페이지의 빈 연락처 테이블을 QA Note 익스텐션으로 캡처하고, 본인 이름/역할/이메일/선호 색상/한마디를 추가하는 이슈를 만듭니다.

진행자는 QA Note AI Fix로 각 이슈를 PR로 만들고, 참가자는 Vercel Preview URL에서 결과를 확인한 뒤 main 브랜치로 머지해 프로덕션 배포까지 확인합니다.

## 수정 위치

참가자 행은 `index.html`의 아래 주석 사이에 추가합니다.

```html
<!-- QANOTE_CONTACT_ROWS_START -->
<!-- QANOTE_CONTACT_ROWS_END -->
```

## 로컬 확인

정적 HTML이므로 별도 빌드가 필요 없습니다.

```bash
open index.html
```
