# 냉동자판기 운영 가이드

냉동자판기 도입 전 입지, 전기·통신, 상품 구성, 냉동 상태 관리, 견적과 계약 조건을 점검할 수 있도록 만든 순수 정적 정보 사이트입니다.

## 사이트 정보

- Organization: `frozen-vending-guide`
- Repository: `frozen-vending-guide.github.io`
- 배포 주소: `https://frozen-vending-guide.github.io/`
- 별도 빌드 과정과 서버가 필요하지 않습니다.

## GitHub Pages 배포

1. GitHub에서 `frozen-vending-guide` Organization을 준비합니다.
2. Organization에 `frozen-vending-guide.github.io` 이름의 Public 저장소를 만듭니다.
3. 이 ZIP의 압축을 푼 뒤, 폴더 안의 파일을 저장소 최상단에 업로드합니다.
4. 저장소의 **Settings → Pages**에서 배포 소스를 **Deploy from a branch**로 선택합니다.
5. Branch는 `main`, 폴더는 `/ (root)`로 지정한 뒤 저장합니다.

배포 후 사이트 주소와 `sitemap.xml`, `robots.txt`가 정상적으로 열리는지 확인하세요.

## 파일 구성

- `index.html` — 메인 콘텐츠와 SEO 메타데이터
- `style.css` — 반응형 디자인
- `robots.txt` — 검색엔진 크롤링 정책
- `sitemap.xml` — 사이트맵
- `404.html` — 오류 안내 페이지
- `favicon.svg` — 사이트 아이콘
