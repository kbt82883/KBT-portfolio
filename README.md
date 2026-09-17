# Portfolio

**Live:** https://kbt82883.github.io/KBT-portfolio/

단일 HTML 파일(`PORTFOLIO.html`)로 만든 개인 포트폴리오 페이지입니다. GitHub Pages로 배포됩니다.

## 구조

| 파일 | 역할 |
|---|---|
| `PORTFOLIO.html` | 포트폴리오 본문. 스타일과 스크립트가 모두 포함된 단일 파일 |
| `index.html` | 저장소 루트 주소로 접속했을 때 `PORTFOLIO.html`로 넘겨주는 리다이렉트 |

## 수정과 배포

`PORTFOLIO.html`을 고친 뒤 `main` 브랜치에 푸시하면 약 1분 뒤 사이트에 반영됩니다.

```bash
git add PORTFOLIO.html
git commit -m "내용 수정"
git push
```

페이지 안의 편집 모드는 브라우저 로컬에만 저장되며, 배포된 사이트는 저장소의 파일로만 바뀝니다.
