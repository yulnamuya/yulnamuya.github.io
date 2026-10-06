# 김미혜 UI/UX 포트폴리오

GitHub Pages에 그대로 올릴 수 있는 정적 사이트입니다. (빌드 과정 없음)

## 올리는 방법
1. github.com 에서 새 저장소(Repository) 생성 — 이름 예: `portfolio`
   - 이름을 `<내아이디>.github.io` 로 만들면 주소가 `https://<내아이디>.github.io/` 가 됩니다.
2. 이 폴더 안의 파일 전체(`index.html`, `img/`, `.nojekyll`)를 저장소에 업로드 (Add file → Upload files)
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save
4. 1~2분 뒤 안내되는 주소로 접속

## 올리기 전에 고칠 곳 (index.html)
- 맨 아래 Contact: `[이메일 주소]`, `[링크]` 를 실제 정보로 교체
- 회사 화면이 포함돼 있으므로 공개 가능 여부를 먼저 확인하세요.
  (`<meta name="robots" content="noindex">` 가 들어 있어 검색엔진 노출은 막지만, 주소를 아는 사람은 누구나 볼 수 있습니다.)

## 참고
- 무료 GitHub 계정에서 Pages는 **공개 저장소**에서만 쓸 수 있습니다. 저장소 안의 파일(이미지 포함)도 누구나 볼 수 있습니다.
- 글꼴(Noto Sans KR)은 Google Fonts에서 불러옵니다.
