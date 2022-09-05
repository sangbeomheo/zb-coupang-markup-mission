# 미션3.카테고리별 추천 광고상품

<br>

## 요구사항

### 1. HTML 마크업

- [x] 1-1. 로고는 문서의 헤더 영역에 포함되도록 마크업하고 헤더는 헤더의 의미를 가지는 시맨틱 요소를 사용해서 마크업해주세요.
- [x] 1-2. 로고는 대제목의 의미를 가지는 `<h1>` 요소의 콘텐츠로 마크업해주세요.
- [x] 1-3. 로고는 `<svg>` 요소를 사용하여 마크업을 작성해주세요.
- [x] 1-4. `<svg>` 요소로 삽입한 로고 이미지의 적절한 대체 텍스트를 제공해주세요.
- [x] 1-5. 로고 이미지를 클릭 시 쿠팡 홈페이지로 이동하도록 하이퍼링크를 지정해주세요.
- [x] 1-6. 카테고리별 추천 광고상품 섹션 영역은 `<section>` 요소로 마크업하고 제목을 제공해주세요. 이때 제목 요소는 `<h2>` ~ `<h6>`을 사용하여야 합니다.
- [x] 1-7. 생활용품 및 주방용품 영역은 `<article>` 요소로 마크업하고 제목을 제목을 제공해주세요. 이때 제목 요소는 `<h2>` ~ `<h6>`을 사용하여야 합니다.
- [x] 1-8. 바로가기 링크의 경우 “>”부분은 배경이미지로 구현하고 마크업은 바로가기 텍스트 만으로 작성해주세요. (바로가기의 하이퍼 링크 경로는 임시로 "/"를 넣어주세요.)
- [x] 1-9. 상품 영역 내 해시 태그는 하이퍼링크를 지정해주세요.(해시 태그의 하이퍼 링크 경로는 임시로 "/"를 넣어주세요.)
- [x] 1-10. 상품 배너 영역은 캐러셀(Carousel) UI의 구조로 구현하고 스크린리더 사용자도 해당 캐러셀의 구조와 내용을 이해할 수 있도록 WAI-ARIA를 사용하여 구현해주세요. 단, 자바스크립트 기능은 구현하지 않아도 됩니다.(캐러셀 UI에 사용할 배너 이미지는 /assets/slides 폴더에 있습니다.)
- [x] 1-11. 상품 카드 링크 이미지는 /assets/category에 제공된 콘텐츠 이미지를 `<img>` 요소로 마크업해주세요.
- [x] 1-12. 상품 카드 링크 이미지에 각각 적절한 대체 텍스트를 제공해주세요.
- [x] 1-13. 상품 카드 링크를 선택하면 각각 상품의 상세 페이지로 연결되도록 하이퍼링크를 지정해주세요.(상세 페이지의 경우 준비된 HTML 파일이 없으므로 파일 경로에 "/"를 넣어주세요.)
- [x] 1-14. 12,900원 등의 가격 정보는 일반 판매가 또는 즉시 할인가, 로켓와우 회원가 정보라는 것을 스크린리더 사용자도 이해할 수 있도록 구현해주세요.
- [x] 1-15. 로켓배송은 `<img>` 요소로 제공하고 적절한 대체 텍스트를 제공해주세요.
- [x] 1-16. 문법 오류가 발생하지 않도록 작성해주세요. HTML 문법 검사 URL : https://validator.w3.org/

### 2. CSS 스타일링

- [x] 2-1. 카테고리별 추천 광고상품 페이지의 스타일은 모두 `/stylesheets/pages/category.css`에 작성해주세요. 이때 색상이나 `rem` 단위를 사용할 경우 `/stylesheets/theme.css` 파일에 제공된 값과 변수를 사용해 주세요.
- [x] 2-2. 로고를 포함한 헤더 영역과 카테고리별 추천 광고상품 섹션은 화면 가운데 배치 되도록 구현해주세요.
- [x] 2-3. 생활용품 및 주방용품 영역 내 바로가기 링크의 `“>”` 부분은 `/assets/icon/angle-right-default.svg` 이미지를 배경으로 지정하여 구현해주세요.
- [x] 2-4. 생활용품 및 주방용품의 배치는 `display : flex`를 활용하여 구현해주세요.
- [x] 2-5. 캐러셀 슬라이드 배너 영역은 하나만 보이도록 설정하고 다른 이미지는 보이지 않도록 구현해주세요.
- [x] 2-6. 캐러셀 슬라이드 배너 캡션과 인디케이터는 `position` 속성을 사용하여 배치해주세요.
- [x] 2-7. 상품카드 영역의 구분선은 가상요소 선택자(::before 또는 ::after)를 이용하여 구현해 주세요.
- [x] 2-8. 크기 및 여백과 다양한 스타일 값은 시안을 참고하여 작성해 주세요.(예 로고의 상단 여백은 100px, 하단 여백은 48px)