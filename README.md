# vue-js-ex

Spring MVC + JSP 환경에서 **Vue.js를 사용한 프론트엔드 연습 예제 프로젝트**입니다.  
Vue CLI 기반이 아니라, **JSP(View) 내부에서 Vue를 사용하는 구조**로 되어 있으며  
기존 레거시 웹 프로젝트에 Vue를 점진적으로 적용하는 방식의 예제를 포함하고 있습니다.

---

## 🎯 프로젝트 목적

- Spring MVC + JSP 기반 프로젝트에서 Vue.js 적용 방식 연습  
- Vue를 SPA가 아닌 **서버 렌더링 + 점진적 적용 구조**로 사용하는 방법 이해  
- 기존 레거시 프로젝트에서 프론트엔드 고도화 시 Vue 도입 연습  
- JSP + Java + Vue 혼합 구조 학습

---

## 📁 프로젝트 디렉토리 구조

현재 저장소는 다음과 같은 구조로 구성되어 있습니다.

```text
vue-js-ex/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/vuejs_ex/
│   │   │        ├── controller/     ← Spring 컨트롤러
│   │   │        └── ...             ← 비즈니스/서버 관련 코드
│   │   │
│   │   ├── resources/               ← application.properties 등 설정 파일
│   │   │
│   │   └── webapp/
│   │       └── WEB-INF/
│   │            └── views/          ← JSP View 영역
│   │                 ├── *.jsp      ← JSP + Vue.js 화면
│   │                 └── ...
│   │
│   └── test/
│       └── java/
│           └── com/example/vuejs_ex ← 테스트 코드 영역
│
└── README.md
