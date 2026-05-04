# Sang Il Lee Sacred Art

외부 방문자용 전시 홈페이지입니다. 화면에 보이는 문구는 영어로 구성되어 있습니다.

## 현재 구성

- `index.html`: 외부 방문자용 메인 전시 페이지
- `img/artworks/fruit-of-the-vine.jpg`: 현재 대표 작품 이미지
- 작품 미리 등록, 업로드 입력폼, 관리자용 기능은 제거했습니다.

## 향후 작품 추가 방법

1. 새 작품 이미지를 `img/artworks/` 폴더에 넣습니다.
   - 예: `img/artworks/madonna-light.jpg`
2. `index.html`에서 `Gallery` 섹션을 찾습니다.
3. 기존 작품 카드 `<article class="art-card">...</article>` 부분을 복사합니다.
4. 이미지 경로, 작품명, 재료, 설명을 새 작품에 맞게 수정합니다.
5. GitHub에 commit/push 하면 외부 방문자에게 반영됩니다.

## 이메일 수정

`your-email@example.com` 부분을 실제 이메일 주소로 바꾸면 됩니다.
