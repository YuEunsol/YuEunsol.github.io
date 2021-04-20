# sol-s-Area



#### 할 것

- [x] headerName 폰트 사이즈 매끄럽게 (2021/03/29)
- [x] 반응형 size 정하기 (2021/03/29)
- [x] 반응형 font size 정하기 (2021/03/29)
- [ ] JS에 DropLine 다 추가
- [ ] JS function(e) 코드 최적화
- [x] #Trapezoid 위치 조정 (2021/04/18)
- [x] dropInterval stop function 수정 (2021/03/29)
- [x] #Trapezoid 반응형에 따른 각도 계산 (2021/04/20)
- [x] DropLine 떨어지는 애니메이션 추가 (2021/03/30)
- [x] media query orientation 모바일 테스트 (2021/04/03)
- [x] #Trapezoid 기울기 수정 (2021/04/28)
- [ ] #Trapezoid .Drop .TrapezoidBackground z-index 수정
- [ ] #p5 왼쪽 공백 삭제 (display: inline-block 안됨 상하 간격 안맞음)
- [ ] 가끔 scroll 빠르게/ 느리게 내릴 시 Dropline 위치 오류나는거 원인 분석
- [ ] calc(vh/vw) 안됨 분석
- [ ] calc -> deg 방법 분석 (2021/04/20) -안쓰기로 함
- [x] css transition <-> js scrollEvent 연동 (2021/03/30)
- [ ] Dropline 색상 바꾸기 (파스텔 톤)
- [x] 튕기는 애니메이션 (2021/04/03)
- [ ] 아래로 떨어질 때 width 살짝 늘어나는 애니메이션 추가
- [x] bounce_ani 매끄럽게 하는 방법 분석 (2021/04/03)
- [x] 떨어지는 유형 나눠서 할지 함수로 할지 결정 (2021/04/03 -> 일단 유형별로)
- [x] 애니메이션 끝난 후 자리 고정 (2021/04/03)
- [ ] bounce_ani drop마다 다르게 랜덤 추가
- [x] drop_ani랑 bounce_ani 시간텀 두기 (2021/04/03)
- [ ] Dropline 그림자 이쁜지 test
- [ ] Dropline 떨어질 때 bold 이쁜지 test
- [ ] Dropline 튕기는 효과 각개설정
- [ ] @keyframes 유형 추가
- [ ] @keyframes 이름 바꾸기
- [x] git repository 옮기기 (2021/04/10) (태훈왕자님이 해주심)
- [ ] Dropline 튕길 때 기울어짐
- [ ] 모바일 .bounce_ani 때 사라짐 수정
- [ ] 모바일 폰트 사이즈 수정
- [ ] 모바일 #HeaderName 사이즈 및 위치 수정
- [x] @media 세로 모바일 데탑 나누기 (2021/04/18)
- [x] scss는 뭐지 (2021/04/18) -안쓰기로 함
- [x] node는 뭐지 (2021/04/18) -안쓰기로 함
- [ ] @media 세로 모바일 데탑 태블릿 테스트
- [x] 코딩 블로그 만들기 (2021/04/18)
- [x] js trapezoid 함수 최적화 (2021/04/20)
- [ ] trapezoid 각도 범위 추가





#### 레이아웃 설계


#### 오늘의 한 마디
2021/04/14 dom 공부하다 프레임워크 공부하고 리액트 알아보고 뷰 알아보고 타입스크립트 프레임워크 장단점 자바스크립트 클린 코드 짜는법 깃 이슈 ... 등등 서핑 좀 즐겼다 뇌가 터질고 같당 결국 react typescript 이렇게 써보기로 했다 일단 환경 빌드부터 해야게따.....저거 위에 것들은 언제 다하지 그리고 개발 블로그 쓰고 싶은데 어디걸로 만들지 고민 중이다 후보는 티스토리 그리고 간혹 코드가 실행되는 블로그가 있던데..?!! 그것도 후보\

2021/04/18 react를 쓰지 않는 것으로 결정했다... 나는 react도 자바스크립트를 쓰는 줄(아주 좀만 고치면 되는 줄) 알았는데 거의 코딩 다시 하는 격... 그리고 코딩 다시 하는 건 문제가 안되는데 애초에 js를 배우기 위해 이 프로젝트를 한 것이기 때문에 그냥 그대로 하기로 결정... 근데 node 까느라 오늘 하루종일 이리저리 갈팡질팡 했는데 억울쓰^ㅡ^ 헤헷 난 다시 js 애니메이션이나 해야겠당 
기울기................진짜 모르겠ㅋ다..........답이 읍ㄱ다............

2021/04/20 드디어 기울기 조정하는 거 해씀 css로 하려던 시도를 다 갖다 버리고 js로 하는 중. tan 0deg = 0, tan 45deg = 1에 맞춰서 하기엔 미세하게 각도 차이가 있어서 범위를 세분화 해서 조건문으로 처리 해야할 것 같으다~~~~ 아 귀차낭 ㅋㅋ 그리고 tan값이 90deg에 가까워졌을 때가 문젠데.. 솔직히 이걸 하는 사람이 있을까 싶지만 _나 같은 애가 할까봐 ㅎㅎ_ 일단 뭐 예외처리를 하든 해야할 것 같다


#### 참고

https://brunch.co.kr/@99-life/5
https://doolyit.tistory.com/202


css 애니메이션 매끄러운 움직임 Cubic-bezier

https://clarle.github.io/yui3/yui/docs/anim/curve.html


jQuery 곡선 패스

https://rgy0409.tistory.com/3890


css animation 마지막 상태 유지

https://webclub.tistory.com/481


css transition 자세한 설명

https://ko.javascript.info/settimeout-setinterval


js setInterval setTimeout 설명

https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Animations/Using_CSS_animations


css animation 설명(eventlistener)

https://zeddios.tistory.com/5


git repository  옮기기

https://imraccoon-developer.tistory.com/11


TypeScript 장단점

https://typescript-kr.github.io/


TypeScript handBook

https://violetboralee.medium.com/react-%EA%B0%9C%EB%B0%9C%EC%9E%90%EB%A5%BC-%EC%9C%84%ED%95%9C-webstorm-%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8-d4f2121909b0


react webstorm plug-in

https://ojava.tistory.com/152


react 개발 환경 구축

https://jaddong.tistory.com/entry/%EB%A6%AC%EC%95%A1%ED%8A%B8-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0


react 개발 환경 구축2

https://medium.com/hivelab-dev/react-js-tutorial-part1-c632e34fc32


react 개념 특징 정리
- 이해 안되는 것 : css 작성 시 대쉬(-)가 들어간 속성명은 카멜 스타일로 바꿔줘야 함 (근데 유지보수나 성능 이슈로 인해 비권장 사항)


https://combatguri.tistory.com/entry/26-rotate-%ED%9A%8C%EC%A0%84%ED%95%98%EA%B8%B0


js rotate




