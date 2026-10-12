# 창업 커뮤니케이션 실습실 · GitHub Pages 배포 패키지

## 파일 구성

- `index.html` — 사이트 시작 파일. 현재 HTML 시안의 전체 화면과 동작이 포함되어 있습니다.
- `.nojekyll` — GitHub Pages가 파일을 Jekyll 처리하지 않고 정적 파일로 제공하도록 하는 빈 설정 파일입니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다. GitHub Free에서는 Pages를 공개 저장소에서 사용할 수 있습니다.
2. 이 패키지 안의 `index.html`과 `.nojekyll`을 저장소 최상위(root)에 올립니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment → Source**에서 **Deploy from a branch**를 선택합니다.
5. 배포 브랜치(일반적으로 `main`)와 폴더 **`/(root)`**를 고르고 **Save**를 누릅니다.
6. Pages가 배포를 마치면 같은 설정 화면에 표시되는 사이트 주소를 엽니다. 주소 형태는 보통 `https://<계정명>.github.io/<저장소명>/`입니다.
7. 모바일 화면, 메뉴 이동, TXT/PDF/PPTX 업로드와 추출을 확인합니다.

## 확인 사항

- 이 사이트는 정적 HTML이며 서버/API나 로그인 기능이 없습니다.
- GitHub Pages 사이트는 인터넷에 공개됩니다. 저장소가 비공개여도 공개된 Pages 사이트에 민감한 정보를 포함하지 마세요.
- 문서 파일은 사이트 방문자의 브라우저에서 처리되며 사이트 서버로 업로드되지 않습니다.
- PDF.js와 ZIP 분석 코드를 CDN에서 내려받으므로 파일 분석에는 인터넷 연결이 필요합니다.
- 스캔 PDF OCR과 구형 PowerPoint `.ppt` 추출은 지원하지 않습니다. `.ppt` 파일은 `.pptx` 또는 PDF로 변환해야 합니다.
- 검토 결과는 기준 키워드와 원문 위치를 확인하는 규칙 검사이며, 전문 평가나 AI 평가가 아닙니다.

## 공식 안내

- GitHub Pages 배포 원본 설정: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- GitHub Pages 사용 제한: https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits
