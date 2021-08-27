# Javascript

## 프로그래밍 언어 문법 공부

> 데이터(자료형)
>
> 변수 - 데이터 타입
>
> 명령 구문 - 조건문(분기문), 반복문
>
> 함수
>
> 객체(Object), Class

### JS Data Type

https://www.w3schools.com/js/js_datatypes.asp

> 자바스크립트는 대체적으로 데이터 타입을 구분하지 않음
>
> Boolean 타입은 별도로 타입 구분됨

### JS Variable

https://www.w3schools.com/js/js_variables.asp
https://www.w3schools.com/js/js_let.asp
https://www.w3schools.com/js/js_const.asp

> var : Es5
>
> let, const : ES6

### JS Operator

https://www.w3schools.com/js/js_operators.asp

> a = a + 1
> => a += 1
> => a++

### JS Condition

https://www.w3schools.com/js/js_if_else.asp

> 조건문 / 분기문
> if구문에 사용되는 condition 식은 결과가 true/false가 나올 수 있는 식
> javascript에서 0 - false, 그 이외의 정수 - true

### JS switch

https://www.w3schools.com/js/js_switch.asp

> expression은 결과가 true/faslse의 형태가 아니고 일반 데이터(숫자, 문자) 형태

### JS Loop For

https://www.w3schools.com/js/js_loop_for.asp

### JS Loop While

https://www.w3schools.com/js/js_loop_while.asp

> 조건문(분기문), 반복문은 프로그램 알고리즘의 논리적인 흐림에 관여하는 명령구문

### JS this

> this 가 사용되는 위치
>
> - Object 안에 있는 method에서 사용 : 포함하는 Object를 가리킴
> - 전역 공간에서 사용 : 전역 객체를 가리킴
> - 함수 공간에서 사용 : 전역 객체를 가리킴

### Javascript에서 사용할 수 있는 객체(제공되는 객체)의 종류

> API : 어플리케이션 프로그래밍을 윟해 여러 서비스/프레임워크/라이브러리에서 제공하는 객체 또는 함수

> HTML API
>
> - geolocation

> ES5/ES6 API(Object) : 내장 객체
>
> - Math, Date

> DOM(Document Object Model)
>
> - HTML Element를 객체로 만든 것

> BOM(Browser Object Model)
> 브라우저와 연관된 객체

> 외부 API
>
> - 지도 API의 객체, 날씨 데이터 API의 객체

### DOM 콘텐츠

> Javascript를 통해서 HTML문서에 없던 콘텐츠를 생성 => 동적(Dynamic) 생성

### Finding DOM

> HTML4
> getElementById()
>
> getElementsByTag()
>
> getElementsByClassName()
>
> HTML5
>
> querySelector()
>
> querySelectorAll()
>
> - 한 종류의 메소드로 id, class, tag 요소로 접근하는데 모두 사용 가능
> - css selector

### Create, Append Element(Node)

> document.createElement()
>
> document.appendChild()

### Vanilla js / jquery

> Vanilla Js : 라이브러리나 프레임워크 사용없이 순수 자바스크립트로 개발하는 것
>
> Jquery : javascript 라이브러리
>
> - $() == $(document).ready() : HTML Element가 모두 랜더링된 이후에 실행

### JS Event

https://www.w3schools.com/js/js_htmldom_events.asp

> Event : 상태 변화
>
> 이벤트 종류
>
> - 마우스 : 클릭, 움직임, 휠...
> - 키보드 : 키 누름...

### JS Event Listener(Handler)

> addEventListener(이벤트, 함수)
>
> - jquery : on()
