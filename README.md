# boostcourse-reviewer-test

## Installation

```sh
$ git clone [THIS_REPOSITORY_ADDRESS.git]
$ cd frontend
$ npm install
$ npm run boot:api-server # Run api server
$ npm start
```

## Spec

> 웹프론트엔드 기술요구사항

- DOMContentloaded 이후에 모든 자바스크립트 로직이 동작하게 합니다.
- 상단영역의 애니메이션은 CSS3의 transition과 transform 속성을 활용해서 구현해야 합니다.
- TABUI로 구성되는 카테고리 아이템이 노출되는 영역의 HTML은 카테고리별로 각각 만들지 않고 하나로 만들어 재사용합니다.
- 카테고리 탭을 선택할 때마다, Ajax 요청을 해서 데이터를 가져와야 합니다.
- 탭 메뉴 (전시/뮤지컬/콘서트 등)는 Event delegation으로 구현합니다.
- Template 코드를 javascript 함수 안에 보관하지 않고, 별도 분리시켜서 사용해야 합니다. (HTML에 script태그 안에 보관한다던가)
- 함수 하나에 여러 개의 기능을 넣지 않고, 함수를 여러 개로 분리합니다.
