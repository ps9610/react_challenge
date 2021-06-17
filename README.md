# react_challenge
리액트JS 2주완성 코드챌린지

- Day 1
  - Class에 Static 사용하기
  - Spread Syntax 사용하여 두 객체 합치기
  - 파라미터에 rest 사용하기
  - Object.freeze()

- Day 2
  - Array.prototype.map()
  - Array.prototype.filter()
  - Array.prototype.reduce()
  - String.prototype.split()

- Day 3 : React를 이용하여 네비게이션 만들기
  - HashRouter를 이용해 router를 완성하고, Link를 사용하여 네비게이션을 만들기
    1) 스크린 만들기
      - Screens 폴더에 있는 Prices, Exchanges, Coins 스크린이 각각 Prices!, Exchanges!, Coins!를 반환.
    2) 파일 불러오기
      - Router.js에서 HashRouter(이름 Router로 바꾸기)와 Route를 불러오기. Screens 폴더에 있는 파일들도 각각 불러오기.
    3) router 만들기
      - router를 만들어 반환. 이 때 exact 속성을 넣어, 중복으로 렌더링이 되지 않도록 하기.
      - Prices 화면은 홈 화면으로서 "/"로 이동되게 하고, exchanges나 coins는 "/"에 각각 exchanges와 coins가 붙인 주소로 이동되도록 하기.
    4) 헤더 만들기
      - Header.js에서 Link를 이용해 헤더 만들기. header태그 안에 ul태그와 li태그를 만들고 그 안에 a 태그와 같은 역할을 하는 Link 넣기.
      - Link를 만들 땐 router 파일을 참고하여 작성. Prices를 누르면 "/"로, exchanges를 누르면 "/exchanges"로, coins를 누르면 "/coins"로 가도록.
    5) 만든 헤더 불러오기
      - Router.js에서 만든 헤더를 불러와 Router 태그 안에 넣기.
