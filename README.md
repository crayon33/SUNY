# SUNY GOLF & GND 랜딩 페이지

골프장 · 리조트 · 호텔 · 콘도 · 요트 등 **레저 부동산 개발·분양·컨설팅** 전문 기업
**㈜써니골프 · ㈜써니지앤디**의 소개 랜딩 페이지입니다.

## 구성

- `index.html` — 단일 파일로 완결된 정적 랜딩 페이지 (HTML + CSS + Vanilla JS, 빌드 불필요)

## 섹션

1. 히어로
2. 회사소개 (GREETINGS)
3. 기업 역량 (CAPABILITY) — 스크롤 진입 시 숫자 카운트업
4. 협력사 (PARTNERS)
5. 프로젝트 수행 (COMPLETED) — 카테고리 탭 필터
6. 브랜드 런칭 (BRAND LAUNCH) — 시니어·레지던스 프로젝트
7. 상담 신청 (CONTACT) — 입력 검증 폼
8. 푸터 (회사 정보)

## 실행

별도 빌드 없이 `index.html`을 브라우저로 열거나, 정적 서버로 서빙하면 됩니다.

```bash
python -m http.server 4173
# http://127.0.0.1:4173/index.html
```

## 참고

- 폰트: [Pretendard](https://github.com/orioncactus/pretendard) (CDN)
- 상담 폼은 프런트엔드 동작만 구현되어 있으며, 실제 접수를 받으려면 전송 엔드포인트 연결이 필요합니다.
