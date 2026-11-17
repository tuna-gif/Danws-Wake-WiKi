# 검신제로 공략 가이드

퀘스트 · 던전 보스 · 전략 카드 · 용어를 한국어/영어로 보는 정적 웹사이트입니다.

- `index.html` : 화면 (수정 거의 불필요. 사이트 이름은 파일 안 `BRAND` 에서 변경)
- `data.json` : 내용 데이터 (용어·카드·상태 설명은 게임 번역 스크립트 1112 기준)
- 주소 끝에 `?lang=en` 을 붙이면 영어로 먼저 열립니다. 예) `https://<계정명>.github.io/sgz-guide/?lang=en#quests`

## GitHub Pages 배포
1. GitHub에서 새 저장소 생성 (Public, 예: `sgz-guide`)
2. **Add file → Upload files** 로 `index.html`, `data.json`, `README.md` 업로드 → Commit
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch `main` / `(root)` → Save
4. 1~2분 뒤 `https://<계정명>.github.io/sgz-guide/` 로 접속

## 내용 수정
`data.json` 을 교체 업로드하면 반영됩니다(1~2분).
