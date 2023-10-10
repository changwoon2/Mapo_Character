# Mapo Character

  ![README](https://user-images.githubusercontent.com/103020096/196095552-3a2400d1-c9e6-4452-8308-a40bd2eb09ad.png)

## 프로젝트 소개

- 2022 마포청년일자리 사업단 동캐릭터 홈페이지입니다.
- 미디어쿼리 1024 PC Tablet 767 712 Mobile 414 기준화면에 맞춰 제작되었습니다.
- [Live Demo](https://mapo-project.github.io/MapoCharacter/)를 통해 페이지를 확인 할 수 있습니다.

---

개발기간 : 2022.09 ~ 2022.10
개발인원 : 1인

- 기획 / 디자인 / 마크업 : 임창운

---

## 개발환경 및 사용툴

- HTML, CSS, JavaScript
- node, bootstrap, jquery
- Visual Studio code
- Git, Github, Github-page

---

## 주요기능

- Bootstrap Reaction type

- 2022 마포 청년 일자리 사업단 동캐릭터 캐릭터소개 턴어라운드 동시계 활동 내역을 전달합니다.

- 부트스트랩 활용한 캐러샐슬라이드 스크롤스파이 모달창

- 자바스크립트 SimpleLightbox 활용한 모달창

---

## 부트스트랩 사용 코드

< HTML Bootstrap> 요소마다 container 사용

* navbar
   - navbar-toggler
   - navbar-brand
   - navbar-nav
   - nav-item
   - dropdown-toggle
   - nav-pills
      
- scrollspy-example

* carouselExampleControls
   - carousel-inner
   - carousel-control-prev, next

- modal-dialog

* card-body
   - card-title
   - card-text email icon을 위한 부트스트랩 CDN사용
   - card-img-top
   
< CSS >

- bootstrap.min.css SimpleLightbox.css

- display: flex 

- flex-direction: column

- justify-content: center 

- align-items: center

- transform: scale 

- transition: all 0.3s ease-in-out

- flex-direction: column-reverse

< JavaScript >

- SimpleLightbox.js

- jquery CDN

- bootstrap.bundle.min.js

---

## 후기

- 부트스트랩으로 프로젝트 참여하면서 코드에대한 이해도가 높아졌습니다

- 부트스트랩 홈페이지에서 제공하는 컴포넌트 활용하여 나와있는코드를 그대로 사용하면서 변경 수정이 필요했습니다

- 레이아웃을 구축하면서 모바일 태블릿 pc 세가지 요소를 완벽하게 보여주기위해서 개발자도구를 활용하며 전체적인 네비게이션바 캐러셀슬라이드 카드 디자인 이해하면서 만들었습니다

- 스크롤스파이같은경우는 원하는 위치에 적절하게 이동하는것인데 a태그를 이용해서 각 제목에 해당하는 곳으로 위치하도록하였습니다

- 모바일같은경우는 햄버거메뉴를 구현하였고 card-body에 해당하는 row col 설정을 적절하게 사용하여 모바일에서는 row-cols-1 태블릿에서는 row-cols-sm-2 pc에서는 row-cols-lg-3 으로   설정하였습니다

- 컨테이너 서브메뉴는 5개 배치하였고 모바일에서는 css flex 활용하여 중앙정렬하였고 텍스트같은경우는 text-align-center 주었습니다

- 이미지는 캐릭터팀에 요청하였고 이미지사이즈를 영역마다 설정하여 너비 높이가 손상되지않게 방지하였습니다 

- 앞으로 부트스트랩을 사용하면서 멋진 홈페이지 만들겠습니다
