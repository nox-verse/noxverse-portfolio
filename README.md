# JIHOO. AI Archive

한국경제 AI 교육 포트폴리오. 샘플 콘텐츠를 담은 반응형 정적 웹사이트입니다.

## 페이지

- dist/article.html: 기사 목록과 본문 상세 보기
- dist/image.html: 이미지 갤러리와 확대 보기
- dist/video.html: 영상 콘셉트 및 스토리보드 (실제 영상은 미등록)
- dist/final.html: 최종 프로젝트 소개와 제작 과정
- dist/index.html: 기사 페이지와 동일한 시작 페이지

`dist/index.html`을 브라우저로 열 수 있습니다. CSS, JavaScript, assets 폴더는 HTML과 함께 유지하세요. 글꼴은 Google Fonts를 사용하며 오프라인에서는 시스템 글꼴로 표시됩니다.

## 수정

각 HTML 파일을 직접 편집할 수 있습니다. `build-pages.cjs`는 초기 페이지 생성 소스이며, 이를 실행하면 dist의 HTML을 덮어씁니다. 상세 기사 본문은 dist/app.js에서 수정합니다. 대표 이미지는 dist/assets/still-life.png입니다.

현재 버전은 콘텐츠 전시를 위한 정적 페이지로, 관리자 로그인·서버 파일 업로드 기능은 포함하지 않습니다. 실제 자료는 HTML 및 assets를 수정해서 게시합니다. 영상 페이지의 재생 모양 버튼은 현재 샘플 스토리보드를 엽니다.

AI로 생성한 이미지 1개와 해당 이미지의 흑백 변형을 사용했습니다. 참고 이미지 원본은 사이트에 포함하지 않았습니다.
