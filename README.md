# React 시험 한 장 정리

React 강의 0~8번(git, HTML, CSS, JavaScript, React 시작, 컴포넌트와 props, 목록과 조건부 렌더링, 이벤트와 state, 입력 폼과 할 일 앱)을 그림과 짧은 코드로 정리한 정적 웹사이트입니다.
하단의 문제은행(42문제)에서 새로고침할 때마다 10문제를 무작위로 뽑아 풀 수 있습니다.

## 구조
- `public/index.html` : 사이트 전체 (HTML + CSS + JS 한 파일, 빌드 과정 없음)
- `wrangler.jsonc` : Cloudflare 배포 설정

## 로컬에서 보기
`public/index.html`을 브라우저로 열면 됩니다.

## 배포
```bash
npx wrangler deploy
```

## 참고
정리 내용은 강의 노션 페이지를 기준으로 작성했습니다. 시험 범위는 강사 안내를 우선하세요.
