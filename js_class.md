# JavaScript 함수 
- 함수를 구성하는 3요소?

 
- 함수가 First Class Citizen 이기 때문에 가질 수 있는 권리

```javascript
// 1. 값 처럼 사용할 수 있다.
// - 1. 변수에 담을 수 있다.
// - 2. 함수의 인자로 사용할 수 있다.
// - 3. 함수의 리턴 값으로 사용할 수 있다.
```

- 함수를 종료시키는 방법

```javascript
//return으로 함수를 return하고 종료한다
function a(a) {
  return a;
}

a(hello);

// break로 강제 종료할수도 있다
```

- 함수를 정의하는 방법
- 함수 Hoisiting이란?

```javascript
// 함수에 Hoisitiong 은 함수가 익명 함수 가 아닐 때 함수 정의를 실행하는 시점을 최상위로 올려준다

hello();

function hello() {
  console.log("hello");
}
```

- 익명함수란?

```javascript
 //함수를 정의할때 이름이 없는 함수 이름을 변수에 넣어서 정의 하기떄문에 Hoisiting 발생하지 않는다

let a = function {
    console.log("aaa")
}
```
