# DAIS Research Group — Site

DAIS (Data Analysis & Intelligence System) 연구 그룹 웹사이트 소스 코드입니다.

라이브 사이트: <https://dais-research.github.io>

## 로컬 개발

[Hugo Extended](https://gohugo.io/installation/)와 [pnpm](https://pnpm.io/)이 필요합니다.

```bash
pnpm install
pnpm dev      # http://localhost:1313
pnpm build    # public/ 디렉토리로 프로덕션 빌드
```

## 콘텐츠 위치

| 경로 | 용도 |
| :--- | :--- |
| `content/authors/` | 그룹 멤버 프로필 |
| `content/publications/` | 논문, 프리프린트, 소프트웨어 |
| `content/gallery.en.md` | 사진 갤러리 |
| `config/_default/params.yaml` | 사이트 정체성·테마·SEO 설정 |
| `assets/media/` | 사이트 자산 (아이콘, 멤버 사진 등) |

콘텐츠는 모두 YAML front matter가 붙은 Markdown 파일입니다. Publications는 BibTeX에서 자동 import 가능합니다 ([.github/workflows/import-publications.yml](.github/workflows/import-publications.yml) 참고).

## 배포

GitHub Pages로 배포되며, `main` 브랜치 푸시 시 [.github/workflows/deploy.yml](.github/workflows/deploy.yml)을 통해 자동 빌드됩니다.

## Credits

[HugoBlox Academic CV](https://github.com/HugoBlox/hugo-theme-academic-cv) 테마 기반으로 제작되었습니다.
