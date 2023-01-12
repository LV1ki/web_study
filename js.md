#변수

```javascript
// const (상수)
// 한 번 할당하면 값의 변경이 불가능하다
// 1. Security 2. Thread Safety

const PI = 3.14;
const daysInWeek = 7;

// number

let a = 1;
a = 1.5;
const b = 2;

// string

a = "str";
a = "str";

// boolean

a = true;
a = false;

// null,undefined

a = null;
a = undefined;

let b;
console.log(b);

console.log(typeof a);
```

#Scope (범위): { }

```javascript
let password = 12345;

{
  let myPassword = 123456789;
  console.log(password);

  {
    let mymypassword = 1;
    console.log(myPassword);
    console.log(password);
  }
}

// console.log(myPassword); // 접근 불가
```

#object (객체)

```javascript
// 1. Array (배열)
// 2. Object (객체)

let name = "a";
let name1 = "b";
let name2 = "c";
let name3 = "d";

let namelist = ["a", "b", "c", "d"];
console.log(namelist[0]);
console.log(namelist.length);
consloe.log(namelist[namelist.length - 1]);

let innerName = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
];

console.log(innerName[0][1]);
console.log(innerName[1][1]);

let variousArray = [1, true, "a", [1, 2, 3], false];

// object
let 이름 = "용수";
let 나이 = 27;
let 주소 = "대구";
```
