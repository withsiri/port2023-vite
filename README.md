# 포트폴리오 사이트 만들기

하나의 웹사이트를 여러 가지 프레임워크를 사용하여 만들어본다
여러 프레임워크들이 어떻게 적용하는지 공부하고, 각 프레임워크들의 장단점을 비교 분석해본다.

1. [vite]
2. [react.js]
3. [vue.js]
4. [next.js]

## 완성작 미리보기
미리보기:

## 사용 스택
- vite(https://ko.vitejs.dev/) 를 사용하여 사이트를 번들링하고 관리
- gsap(https://greensock.com/gsap) 를 이용하여 패럴랙스 효과 구현
- lenis(https://lenis.studiofreight.com/) 를 이용하여 스무스 효과를 구현
- netlify(https://www.netlify.com/) 를 통해 사이트를 배포
- HTML, CSS 기반으로 웹사이트 기본 레이아웃을 설계하고, 웹표준 및 웹 접근성을 준수하여 작업[ARIA(Accessible Rich Internet Applications)](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/Roles)

## 프로젝트 실행
- vite 설치 `npm create vite@latest`
- gsap 설치 `npm install gsap`
- lenis 설치 `npm install @studio-freight/lenis`
- vite를 설치 후 환경 설정 `vite.config.js`파일을 생서하고 다음과 같이 작성.
```javascript
export default {
    root: "src",
    build: {
        outDir: "../public",
    },
};