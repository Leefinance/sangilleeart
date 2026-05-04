# Sang Il Lee Art 홈페이지

기존 Bootstrap 기반 정적 홈페이지를 개인 미술 전시 홈페이지 형태로 수정한 버전입니다.

## 주요 기능

- 메인 히어로 영역
- 작품 갤러리 카드형 전시
- 회화 / 드로잉 / 디지털 분류 필터
- 작품 클릭 시 상세 모달 보기
- 브라우저 로컬 저장 방식의 작품 미리 등록 기능
- 모바일 반응형 레이아웃

## 실제 작품을 홈페이지에 반영하는 방법

1. 작품 이미지를 `img/artworks/` 폴더에 넣습니다.
2. `index.html` 하단의 `const artworks = [...]` 목록에 작품 정보를 추가합니다.

예시:

```javascript
{ title:'작품명', year:'2026', category:'회화', medium:'Acrylic on canvas, 72.7×60.6cm', image:'img/artworks/my-art.jpg', desc:'작품 설명' }
```

## 주의

`Add Artwork` 기능은 정적 홈페이지에서 테스트할 수 있는 로컬 미리보기 기능입니다. GitHub Pages 같은 정적 호스팅에서는 방문자가 업로드한 이미지를 서버에 자동 저장할 수 없습니다. 실제 온라인 업로드 기능이 필요하면 Firebase, Supabase, Netlify Forms, 별도 백엔드 서버 등이 필요합니다.
