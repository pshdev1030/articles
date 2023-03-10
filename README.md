# articles

인상깊게 읽은 아티클들

## React

- [React as a UI Runtime](https://overreacted.io/react-as-a-ui-runtime/) : 리액트의 프로그래밍 모델에 대한 설명, 베타독스의 내용과 조금 겹침!
- [react-hooks-lifecycle](https://github.com/Wavez/react-hooks-lifecycle) : hooks의 라이프사이클
- [Making setInterval Declarative with React Hooks](https://overreacted.io/making-setinterval-declarative-with-react-hooks/) : 위의 hooks의 lifecycle에서 ref와 클로저를 활용하여 setInterval을 react lifecycle과 동기화하기
- [A Complete Guide to useEffect](https://overreacted.io/a-complete-guide-to-useeffect/) : useEffect에 대한 아티클, 리액트의 렌더링을 스냅샷으로 바라볼 수 있도록 이해를 도움 !
- [Avoiding useEffect with callback refs](https://tkdodo.eu/blog/avoiding-use-effect-with-callback-refs#interacting-with-refs) : callbackRef를 사용하여 useEffect를 사용하지 않고 DOM 노드의 렌더링 직후 effect를 실행하는 방법
- [참조 동일성을 위한 메모이제이션](https://yceffort.kr/2022/04/memo-for-referential-stability-in-react#%EC%99%9C-%EB%AA%A8%EB%93%A0-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EB%A5%BC-memo-%ED%95%B4%EC%95%BC-%ED%95%98%EB%8A%94%EA%B0%80) : ref, useMemo, useCallback과 리액트에서의 메모이제이션
- [React.memo() 현명하게 사용하기](https://ui.toast.com/weekly-pick/ko_20190731) : memo 현명하게 사용하기
- [React hooks - useEffect: HTTP requests ](https://im-developer.tistory.com/211) : 리액트에서의 비동기 요청에서의 에러, promise의 상태, 데이터등을 하나의 데이터로 바라보아야 한다는 인사이트를 얻을 수 있다!
- [\[번역\] React에 SOLID 원칙 적용하기](https://dev-boku.tistory.com/entry/%EB%B2%88%EC%97%AD-React%EC%97%90-SOLID-%EC%9B%90%EC%B9%99-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0) : 컴포넌트 설계시에 고려해야 할 점. 상속대신 합성을 주로 사용하는 리액트에 SOLID 원칙을 적용하는 아티클이다.
- [더 나은 컴포넌트 설계하기](https://velog.io/@juno7803/%EB%8D%94-%EB%82%98%EC%9D%80-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%84%A4%EA%B3%84%ED%95%98%EA%B8%B0#%EC%9D%B8%ED%84%B0%ED%8E%98%EC%9D%B4%EC%8A%A4) : 도메인 지식을 빼는 등 좀 더 제너럴한 컴포넌트를 설계하는 방법
- [Uploading Images to S3 from a React Single Page Application](https://medium.com/developing-koan/uploading-images-to-s3-from-a-react-single-page-application-45a4d24af09f) : spa에서 AWS S3 presignedURL를 이용하여 이미지 업로드하기

## Javascript

- [How JavaScript Timers Work](https://johnresig.com/blog/how-javascript-timers-work/) : Javascript setTimeout과 setInterval의 차이점
- [Tasks, microtasks, queues and schedules](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/) : 자바스크립트 이벤트루프와 마이크로 태스크 큐, 태스크 큐의 개념
- [High Performance JavaScript by Nicholas C. Zakas](https://www.oreilly.com/library/view/high-performance-javascript/9781449382308/ch04.html) : 자바스크립트에서의 반복문들과 조건문들의 성능비교, Object literal을 쓰자!
- [eventloop spec](https://html.spec.whatwg.org/multipage/webappapis.html#event-loops) : 이벤트루프 스펙
- [Exploration of requestAnimationFrame execution mechanism](https://segmentfault.com/a/1190000040945949/en) : requestAnimationFrame의 동작원리
- [인간 JS 엔진되기](https://youtube.com/playlist?list=PLcqDmjxt30Rt9wmSlw1u6sBYr-aZmpNB3) : 쉽게 알아보는 자바스크립트에서의 비동기(Promise,Async,Await ...)
- [requestIdleCallback으로 최적화하기](https://yceffort.kr/2021/08/requestIdlecallback) : requestIdleFrame을 이용한 최적화, 브라우저가 idle 상태일 때 작업을 지시하는 방법과 적절한 사용예시
- [JavaScript: HTML Form Validation](https://www.w3resource.com/javascript/form/javascript-form-validation.php) : HTML Form validation 가이드

## CSS

- [Defensive CSS](https://defensivecss.dev/) : 버그를 야기하지 않는 CSS 작성예시
- [flexbox로 만들 수 있는 10가지 레이아웃](https://d2.naver.com/helloworld/8540176) : CSS Flexbox를 활용한 10가지 레이아웃
- [Aspect Ratio Boxes](https://css-tricks.com/aspect-ratio-boxes/) : CSS를 활용하여 이미지나 비디오 비율 유지하기
- [The trick to viewport units on mobile](https://css-tricks.com/the-trick-to-viewport-units-on-mobile/) : 모바일 기기 100vh 대응하기
- [반응형 웹 디자인 기초](https://web.dev/responsive-web-design-basics) : 모바일을 고려한 반응형 가이드

## Browser
- [CRP](https://developer.mozilla.org/en-US/docs/Web/Performance/Critical_rendering_path) : critical rendering path에 대하여
- [Adding Interactivity with JavaScript](https://web.dev/critical-rendering-path-adding-interactivity-with-javascript/) : CRP에서 javascript가 동작하는 원리
- [CSS 성능 향상 시키기](https://yceffort.kr/2021/03/improve-css-performance) : CRP에서 css와 stylesheet가 동작하는 원리
- [https://yceffort.kr/2022/06/preload-scanner](https://yceffort.kr/2022/06/preload-scanner) : 프리로드 스캐너에 대하여


## DesignSystem

- [리메인 디자인시스템](https://www.remain.co.kr/page/designsystem/color-wraning.php) : ui개발자로서 알아두면 좋은 내용들!
- [Build strongly typed polymorphic components with React and TypeScript](https://blog.logrocket.com/build-strongly-typed-polymorphic-components-react-typescript/) : Typescript를 사용하여 dx를 고려한 공용 컴포넌트를 만드는 방법
- [Advanced React For Enterprise: React for senior engineers](https://www.udemy.com/course/react-for-senior-engineers/) : 디자인 시스템의 목적, scss를 활용하여 확장가능한 프론트엔드 환경을 구축하는 방법
- [Pure CSS Custom Checkbox Style](https://moderncss.dev/pure-css-custom-checkbox-style/) : CSS만을 사용한 체크박스 만들기, 디자인 시스템의 구현에 있어서 기본적인 브라우저 동작의 지원과 크로스브라우징을 고려해야함을 알 수 있음!
- [CSS in JS 라이브러리에서 Typesafe하게 Theme 관리하기](https://tech.devsisters.com/posts/react-extend-theme/) : CSS in JS 환경에서 Context API + Typescript를 이용해서 확장 가능한 Theme을 관리하는 방법

## Error

- [에러 처리를 어떻게 하면 좋을까? - 2](https://www.rinae.dev/posts/how-to-handle-errors-2) : 커스텀 에러 클래스를 정의하거나, 에러 모나드를 만드는 등, 어플리케이션에서 에러를 정의하고 다루는 방법
- [\[Track 1-2\] 유인동 - ES6+ 비동기 프로그래밍과 실전 에러 핸들링](https://www.youtube.com/watch?v=o9JnT4sneAQ) : try catch로 하는 예외처리의 한계와, 예외는 터뜨리고 실제 사용하는 쪽에서 핸들링하는게 바람직하다는 관점과 이런 관점에서 표현식의 이점과 함수형 프로그래밍의 장점에 대한 인사이트를 얻을 수 있음!
- [Using Facebook's invariant vs if throw](https://stackoverflow.com/questions/39055159/using-facebooks-invariant-vs-if-throw) : 에러로부터 좀 더 견고한 소프트웨어를 만들기위한 facebook의 invariant 모듈, 선언형으로 예외처리를 한다는 이점과 개발환경에서만 에러를 throw하는 모듈. 

## Conference

- [\[A6\] Statecharts: 복잡한 UI 상태를 지배하는 방법](https://www.youtube.com/watch?v=Hv_PhrfwerQ) : ui 개발을 상태와 액션으로 바라보는 시각을 제시하는 발표, 유한상태머신
- [\[Dev Dive_ Frontend Day\] 내 코드의 품질을 높여주는 Type-Driven Development](https://www.youtube.com/watch?v=M3pMCZqPvzI&t=841s) : 타입스크립트 컴파일러를 활용하여 안정적인 소프트웨어를 만드는 방법과 원칙
- [\[A1\] 웹뷰에서 다크모드 상속받기: 일관성있는 사용자 경험을 위하여](https://www.youtube.com/watch?v=ElsZ-v4Ow08&t=1s) : 다크모드에서의 깜빡임을 제거하기 위한 설계 렌더링 블록과 헤더, 캐싱을 고려한 전략이 인상적임!


## Accessibility
- [레진 웹 접근성 가이드라인](https://github.com/lezhin/accessibility) : 웹 접근성에 대한 가이드라인
- [레진 WAI-ARIA 가이드라인](https://github.com/lezhin/accessibility/tree/master/aria) : aria 가이드라인

## etc
- [Apple developer](https://developer.apple.com/documentation/technologies) : shell을 이용하여 mac의 os레벨에 접근해야 할 경우 참조할 수 있는 문서
- [Launch the default app for a URI](https://learn.microsoft.com/en-us/windows/uwp/launch-resume/launch-default-app#standard-shell-related-uri-schemes) : shell을 이용하여 window의 os레벨에 접근해야 할 경우 참조할 수 있는 문서
