# CSS Animation 구현
## 🙃 미션
css animation 관련 속성을 사용해서 기능들을 구현해보자

## 기능들

### infinite slide
- 슬라이드는 이미지 4개가 존재한다.
- 슬라이드는 2초마다 자동으로 넘어가며 넘어가는 시간은 0.5초이다.
- 마지막 슬라이드라면 첫번째 슬라이드로 넘어간다.

https://user-images.githubusercontent.com/32596517/156597468-60eaf04c-ff69-4ea0-873e-deeeede66519.mov

<br/>

### play-state
- UI는 아래 동영상과 같이 이미지들과 그 위에 mask가 존재한다.
- mask는 영상처럼 좌에서 우로 움직인다.
- 이미지에 hover시 mask가 멈춘다.

https://user-images.githubusercontent.com/32596517/156597491-1ac3ff5d-e229-40e0-bee1-db7411af7df5.mov

<br/>

### Countdown
- 숫자가 5에서 부터 1초마다 1씩 감소하며 5초가 지나면 종료된다.
- 5초가 지나 카운트다운이 종료되면 숫자(0)의 색깔은 빨간색이 되며 "카운트다운 종료" 텍스트가 하단에 표시된다.

https://user-images.githubusercontent.com/32596517/156597503-1448f0e8-dc3f-4ffb-b85c-372352927185.mov

<br/>

### Size
- 페이지 가운데 박스가 존재한다.
- 박스는 다음의 step들을 1초의 duration을 가지고 진행하며 무한반복한다.
  1. height 증가
  2. width 증가
  3. width 감소
  4. height 감소
```css
  /* size: 100px -> 300px */
  box-shadow:  10px 10px 10px #ccc;
```

https://user-images.githubusercontent.com/32596517/156597525-a8454dcc-3492-4146-ba8b-734180d3d8b6.mov

<br/>

### Hover
- Title에 hover시 텍스트에 color bar가 왼쪽에서부터 나타난다.
- hover를 벗어나면 다시 왼쪽에서부터 사라진다.
- 텍스트는 html에 제공된 텍스트를 사용한다.

https://user-images.githubusercontent.com/32596517/156597536-e96ea8f2-b087-4eec-ab25-1b2a755758d0.mov