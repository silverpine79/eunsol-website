# EUNSOL LEE · Portfolio

정적 포트폴리오 사이트 (HTML·CSS 한 파일).

- `public/index.html` — 홈페이지
- `public/images/` — profile.jpg, project1.jpg~project3.jpg 를 넣으면 표시됨
- `wrangler.jsonc` — Cloudflare Workers 정적 에셋 배포 설정

## 배포
Cloudflare 대시보드 → Workers & Pages → Create → Import a repository → 이 저장소, 브랜치 `main` 선택.
빌드 명령 없음, 배포 명령 `npx wrangler deploy`.
