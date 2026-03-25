# DOM

---

## DOM조작

---

DOM 조작이란 HTML 요소를 JavaScript로 선택하고, 생성하거나 수정하여 웹 페이지의 내용을 동적으로 변경하는 것을 의미

---

### 요소선택

요소선택 : document.querySelector , document.querySelectorAll

-document.querySelector -> CSS 선택자를 사용하여 특정 요소 하나를 선택하는 메서드이다. 조건에 맞는 요소가 여러 개일 경우, 가장 먼저 나오는 요소 하나만 반환

-document.querySelectorAll -> CSS 선택자를 사용하여 여러 요소를 한 번에 선택하는 메서드이다. 선택된 요소들은 리스트 형태(NodeList)로 반환되며, 반복문을 통해 각각 접근가능

---

### 요소 생성/수정

요소생성/수정:createElement , appendChild , innerHTML , textContent

-createElement -> 새로운 HTML 요소를 생성할 때 사용하는 메서드이며, 예를 들어 div, p 같은 태그를 JavaScript로 만들기가능

-appendChild -> 생성된 요소를 특정 부모 요소의 자식으로 추가할 때 사용하는 메서드이며, 즉, 만든 요소를 화면에 보이게 할 때 사용

-innerHTML -> 요소 내부의 HTML 내용을 문자열 형태로 설정하거나 가져오는 속성이며, HTML 태그를 포함한 내용을 한 번에 변경가능

-textContent -> 요소 내부의 텍스트 내용만을 설정하거나 가져오는 속성이며, HTML 태그는 적용되지 않고, 순수한 문자열만 처리
