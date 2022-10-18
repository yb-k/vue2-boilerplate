# vue2-boiler-plate

## 설명
뷰2 보일러 플레이트입니다.

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

## 폴더 구조
- public : 정적 리소스 폴더로 이폴더에 있는 파일들은 그대로 `COPY`됩니다. (브라우저 라이브러리 적용)

- src
  - assets : 번들러를 통과하는 정적 리소스를 작성합니다.
  - common : 공통 소스를 작성합니다.
    - component.golbal.js : 전역 컴포넌트를 선언 / 관리
    - config : 앱 내 설정 관리
    - constatns : 상수
    - helpers : 헬퍼 함수 정의
  - components : 컴포넌트 파일 관리
    - common : 공통/전역/하위 레벨의 컴포넌트 관리
  - layouts :  레이아웃 컴포넌트 선언 (with `vue-router-layout`)
  - middlewares : 미들웨어 관리 / 화면 이동 관련
  - modules : 모듈 관리 / SERVER API에 대응되는 store + component 관리
  - plugins : 플러그인 관리 및 확장
  - router : vue-router 설정 관련
  - services : SERVER API에 대한 서비스 관리
  - store : vuex 설정 관련
  - validate : vee-validate 설정
  - views : 페이지 컴포넌트 (with `vue-auto-routing`)
## 관련 pacakges
### 코어
[Vue v2](https://v2.vuejs.org/)
[Vue Router](https://router.vuejs.org)
[Vuex](https://vuex.vuejs.org/)
[Vue Cli](https://cli.vuejs.org/)

[vue-cli-plugin-auto-routing](https://github.com/ktsn/vue-cli-plugin-auto-routing)

### 플러그인
[vue-fragment](https://github.com/Thunberg087/vue-fragment)
[vee-validate v3](https://vee-validate.logaretm.com/v3/)

### 유틸
[dayjs](https://day.js.org/)
[lodash](https://lodash.com/)