
# 성경 토글 사이트 (GitHub Pages 배포)

- `index.html`: 성경(권 → 장 → 단락 → 본문) 토글 열람
- `sermon.html`: 설교 편집/보존 페이지 (ChatGPT 출력 내용 붙여넣기 가능)

## 배포 방법
1. 새 GitHub 저장소 생성 후, 두 파일을 업로드합니다.
2. 저장소 **Settings → Pages**에서 **Deploy from a branch** 설정.
3. **Branch: main** / **root**를 선택 후 저장. 잠시 뒤 노출되는 URL로 접속하세요.

> 본문과 단락 정보는 사용자가 업로드한 `bible.json`, `bible-paragraphs.txt`를 바탕으로 정적 페이지가 생성되었습니다.
