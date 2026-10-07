# 부산 시민 AI 체험의 날

부산 시민 AI 체험의 날 행사 홍보 웹페이지입니다.

배포 주소: https://ukbang.github.io/busan-event-webpage/

## 파일

- `event_homepage.html`: HTML, CSS, 메뉴 동작을 포함한 원본 파일
- `index.html`: GitHub Pages에서 표시하는 원본과 동일한 페이지
- `.nojekyll`: 정적 HTML 파일을 그대로 배포하기 위한 설정
- `AGENTS.md`: 행사 정보 및 프로젝트 작업 규칙

기획 문서와 참고자료는 로컬 `outputs/`, `data/`에 보관하며 저장소에 업로드하지 않습니다. 제공되지 않은 행사 정보는 ‘미정’으로 표시합니다.

## 수정 및 배포

`event_homepage.html`을 수정한 뒤 `index.html`에도 같은 내용을 반영합니다.

```sh
cp event_homepage.html index.html
git add event_homepage.html index.html
git commit -m "Update event webpage"
git push origin main
```

GitHub Pages는 `main` 브랜치의 루트 폴더(`/`)에서 배포합니다.
