### react
not framework. library!
compose component.

virtual dom vs real dom

virtual dom의 스냅샷을 찍어놓고
변경사항과 스냅샷을 비교하여 바뀐 부분을 찾음(diffing)
바뀐 부분만 real dom에서 변경해줌
-> dom을 매번 새롭게 다시 만들어 줄 필요가 없음.

### node version
node -v v16.13.0

### babel
최신 자바스크립트 문법을 구형 브라우저에서 돌 수 있게 변환 시켜줌

### webpack
서로 의존성을 가지는 여러 파일들을 간단한 파일로 바꿔줌
src 폴더 안의 파일들만 관리를 해준다.

### create-react-app(window)
npx create-react-app 앱이름

### run react
npm run start (command scripts in package.json)


### folder
_actions
_reducer
-> redux를 위한 폴더

components/views
-> Page를 넣는 폴더
ex) LandingPage: 첫 화면
LoginPage: 로그인 화면
NavBar: 네비게이션 바

components/view/Sections
-> 해당 페이지에 관련된 css파일이나 component들을 넣는 폴더

App.js
-> Routing 관련 일을 처리하는 파일

Config.js
-> 환경 변수 같은 것들을 정하는 파일

hoc
-> Higher Order Component의 약자로 페이지 접근 권한을 설정하는데 쓰임

utils
-> 여러 곳에서 쓰일 수 있는 것들을 넣을 곳

### extensions
ES7 React/Redux/GraphQL/React-Native snippets: rfce, rcce를 타이핑해서 컴포넌트를 자동 생성해줌