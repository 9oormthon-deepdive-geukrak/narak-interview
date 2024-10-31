# HTML

## DOCTYPE

&nbsp;

### 1. DOCTYPE에 대하여 설명하시오

- Document Type Declaration(DTD)
  - HTML5는 DTD를 참조할 필요 없이 `<!DOCTYPE html>`로 선언할 수 있다.
- 문서 형식 선언
- 선언된 페이지의 HTML 버전이 무엇인지 웹 브라우저에 알려주는 역할을 하는 선언문

&nbsp;

### 2. meta 태그에 대해서 알고 있나요?

- 문서에 대한 정보인 메타데이터(metadata)를 정의할 때 사용
- `<head>`요소 내부에 위치

&nbsp;

### 3. meta 태그의 요소에 대해서 아는대로 말해보세요

1. `charset`:문서 인코딩에 사용한 문자 인코딩을 나타내는 "문자 집합 선언"
2. `content`: `http-equiv` 또는 `name` 특성의 값
3. `http-equiv`: HTTP 헤더가 제공하는 정보와 동일한 "프래그마 지시문"
   - `content-security-policy`: 허용할 서버 출처와 스크립트 엔드포인트를 지정
   - `content-type`: 지정할 경우, `content` 특성의 값은 반드시 `text/html; charset=utf-8`
   - `default-style`: 기본 CSS 스타일 시트 세트의 이름을 지정
   - `x-ua-compatible`: 지정할 경우, `content` 특성의 값은 반드시 `IE=edge`
   - `refresh`
     - `content` 특성의 값이 양의 정수인 경우: 페이지를 다시 불러오기 전가지의 초 단위 대기시간
     - `content` 특성의 값이 양의 정수를 가지고 그 뒤를 문자열 `;url=`과 유효한 URL이 뒤따를 때: 해당 URL로 이동하기 전까지의 초 단위 대기시간
4. `name`: 전체 페이지에 적용되는 "문서 레벨 메타데이터"
   - [표준 메타데이터 이름](https://developer.mozilla.org/ko/docs/Web/HTML/Element/meta/name)
