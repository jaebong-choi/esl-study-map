# ESL Study Map — 영국 · 아일랜드 · 몰타 어학연수 지도

영국·아일랜드·몰타의 어학원 캠퍼스와 기숙사를 지도에서 탐색하는 무료 정보 지도입니다. 특정 유학원·기관과 무관하며, 학교별 상세 정보는 각 어학원 공식 홈페이지로 연결됩니다.

## 주요 기능

- **국가 → 도시 → 캠퍼스 드릴다운** — Leaflet + CartoDB Voyager 지도에서 단계별 탐색
- **13개 어학원 브랜드, 40+ 캠퍼스** — Kaplan · EC · Bayswater · CES · English Path · Emerald · Atlas · IELS · CEA · IH London · LSI · St Giles · ILSC (브랜드 컬러 약칭 배지)
- **기숙사 마커** — 캠퍼스 선택 시 소속 기숙사 위치·타입·통학 정보 표시
- **학교 공식 홈페이지 연결** — 캠퍼스 상세에서 각 브랜드 공식 사이트와 Google 지도 위치로 바로 이동
- **국가별 공식 정보** — English UK / ACELS / FELTOM 인증기관과 정부 비자 공식 안내 링크
- **3개 언어** — 한국어 / English / 繁體中文 (UI·데이터·기숙사 구문 번역)

## 구조

- `index.html` — 지도·패널·데이터(SCHOOLS/CITIES/CAMPUSES)
- `res-data.js` — 캠퍼스 좌표·주소(CENTER_INFO), 기숙사(RES)
- `i18n.js` — UI 사전, 데이터 번역 오버레이(L10N), 기숙사 구문 사전(RES_PH)

## 면책

본 지도는 정보 제공 목적이며, 과정·가격·기숙사 정보는 각 어학원 공식 사이트 기준이 우선합니다. 비자 요건은 각국 정부 공식 사이트에서 확인하세요.
