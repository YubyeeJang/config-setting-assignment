# 환경설정, 회원가입 모달 과제

## 내용

[Git Subtree](https://ohmy0418.notion.site/IDP-Subtree-99b643e15cae4238b3d1cd5b824c5a13)를 사용해서 style-core를 가져오고, style-core 디자인 가이드를 베이스로 마크업 작성을 한다.

## 폴더 설명

### dist

Webpack 번들링 후 생성되는 최종 output 폴더

`npm run dev` 명령어를 입력하면 한번 삭제되고, 최신 src 코드로 번들링 된다.

### src

작업자가 실제로 작성하는 폴더

\*\*src/style-core\*\*

- Git Subtree 로 등록한 IRIS-Design-Core 레파지토리 코드가 담겨있는 폴더

\*\*src/views\*\*

- 필요에 따라서 영역 별로 모듈화 시켜서 마크업 작성이 가능

### views

- src/views에서 분리시켜 작업한 html 코드가 통합되어 나오는 output

## 참고

- style-core는 수정, 변경하지 않고 컴포넌트 단위를 참고해서 클래스를 가져다 씁니다.
