# Neon Idol

AI 아이돌 육성 리듬 게임 · 웹 배포판 (tools/build-web.mjs 로 생성)

- 카메라(댄스 · 작곡)와 마이크(보컬)를 사용합니다. 처음 실행할 때 브라우저의 권한 요청을 허용해 주세요.
- **https 주소(GitHub Pages)** 에서 실행해야 카메라 · 마이크가 동작합니다. 파일을 더블클릭해서는 실행되지 않습니다.
- 크롬 · 엣지 최신 버전을 권장합니다.

## GitHub Pages 로 올리기
1. GitHub 에서 새 저장소(Public)를 만듭니다. 예 : `neon-idol`
2. 이 폴더 안의 **모든 파일과 폴더**(숨김 파일 `.nojekyll` 포함)를 저장소 맨 위(루트)에 올립니다.
   - 웹 화면의 드래그 업로드는 한 번에 100개까지라, 폴더별로 나눠 올리거나 GitHub Desktop 을 쓰면 편합니다.
3. 저장소 **Settings → Pages** 에서 Source 를 `Deploy from a branch`, Branch 를 `main` / `/(root)` 로 저장합니다.
4. 1~2분 뒤 `https://<아이디>.github.io/<저장소 이름>/` 주소로 접속할 수 있습니다.
