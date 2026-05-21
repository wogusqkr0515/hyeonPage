# Hyeon Blog

GitHub Pages에서 바로 배포할 수 있는 정적 블로그입니다.

## 로컬에서 보기

브라우저에서 `index.html` 파일을 열면 됩니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더를 저장소에 푸시합니다.
3. 저장소의 `Settings` → `Pages`로 이동합니다.
4. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, folder는 `/root`로 설정합니다.

배포가 끝나면 `https://<github-id>.github.io/<repository-name>/` 주소로 접속할 수 있습니다.

## 새 글 추가

1. `posts` 폴더에 새 HTML 파일을 만듭니다.
2. 기존 `posts/hello-github-pages.html` 구조를 복사해 내용을 수정합니다.
3. `index.html`의 `최근 글` 섹션에 새 글 링크를 추가합니다.

## 파일 구조

```text
.
├── index.html
├── about.html
├── 404.html
├── styles.css
├── posts/
│   └── hello-github-pages.html
└── README.md
```
