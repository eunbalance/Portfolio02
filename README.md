# Eunsu Kong — UX/UI Portfolio

빌드 도구 없이 동작하는 정적 사이트.

- `index.html` — 메인 (WHY / CTA / Highlights / Work / About + 이력서 오버레이)
- `project.html` — 프로젝트 상세 (`?p=vivizip` | `kb` | `musinsa` | `co-hi`)

이미지·폰트·렌더 스크립트가 파일 내부에 모두 포함되어 있습니다.

## Vercel 배포
1. 이 폴더 전체를 GitHub 저장소에 push
2. Vercel → New Project → 저장소 선택
3. **Framework Preset: Other**
4. Build Command: 비움 / Output Directory: 비움 (루트)
5. Deploy

## 로컬 확인
`index.html`을 브라우저로 열면 됩니다.
