# React! React! React! 
- 플러터 라이센스 등록 실패, 플러그인 설치 실패로 인해.. 갈 길 잃은 망망이는 리액트라도 다시 공부해보자 악을 품는데...

## ⚽ React? React-native?
- React-native
  - 페이스북에서 모바일용 '네이티브 앱'을 쉽게 만들 수 있게 하는 자바스크립트 라이브러리
  - 장점) 한 번에 안드-iOS 지원하는 앱 개발 가능 (기존: 안드-안드스, iOS-Swift) → 시간&인력 줄임, 네이티브 코드로 컴파일 되어 성능 좋고 최신 OS 플랫폼에도 지원 
  - 단점) 외부 라이브러리 부족, 복잡한 설정은 따로 구현해야 해서 시간&비용 소요
- React
  - 페이스북에서 만든 오픈소스, FE의 UI를 만드는 자바스크립트 라이브러리 (최근 FE lib.로는 Angular,Vue-모두 'js lib.')
  - 장점) 객체지향의 개념으로 자주 쓰이는 화면의 UI를 부분적으로 컴포넌트화한 캡슐화로 간편 수정, 재사용 (MVC 개발의 V에 집중해 UI 구현 수월)
  - 단점) V에 집중을 해서 라우팅, 데이터 모델링 부분 등 없는 기능은 다른 lib.를 사용해야 함

리액트 이론) https://goddaehee.tistory.com/293

### ⚾ React 프로젝트 시작하기 
with. https://react.codepot.kr/docs/week01/doc2/
- [x] install Node.js
- [x] create react app
- 회사 컴으로 해서 그런지 SSL 등 제약이 너무 많았다.. `happy hacking!` 이 어찌나 반갑동지.

#### 🤷‍♂️ 클래스형 컴포넌트? 함수형 컴포넌트?
클래스형 컴포넌트
- state 기능, 라이프 사이클 기능 사용
- 임의 메서드 정의 불가
- <strong>render</strong> 함수 꼭 있어야 하며, 그 안에서 보여줘야 할 <strong>JSX</strong> 반환  

함수형 컴포넌트
- 선언하기 편리하며, 메모리 자원 덜 사용
- 과거에는 함수형 컴포넌트에서 state와 라이프 사이클 API를 사용할 수 없었지만 --> 리액트 훅이 도입되면서 해결
- 일반적인 함수 선언 방식, ES6의 화살표 함수(arrow func.) 방식  
- function() 자신이 종속된 객체를 this로 가리킴
- function()=>{} 자신이 종속된 인스턴스를 가리킴



- search. 라이프 사이클? 리액트 훅? ES6?
리액트 이론 심화) https://devowen.com/298
