<!-- class vs object 비교 -->

# class vs object

## class vs object 특징 비교

### \* class

- template
- declare once
- no data in
- 비유표현: 붕어빵을 만들 수 있는 틀

### \* object

- instance of a class
- created many times
- data in
- 비유표현: 팥붕어빵, 크림붕어빵, 피자붕어빵

#### class = fields + methods

### \* 형식

```js
class person{
  name; // 속성(field)
  age; // 속성(field)
  speak(); // 행동(method)
}
```

### \* 예시

#### class 선언

```js
class Person {
	constructor(name, age) {
		this.name = name;
		this.age = age;
	}
	speak() {
		console.log(`${this.name}: hello!`);
	}
}
```

#### object 생성

```js
const misung = new Preson("misung", 20);
console.log(misung.name);
console.log(misung.age);
misung.speak();
```

---

---

<!-- Function 함수에 관하여 -->

# Function

## Function에 대한 특징

### \* Function?

- fundamental building block in the program (프로그램 안에서의 각각의 작은 단위)
- subprogram can be used multiple times (여러번 재사용이 가능)
- performs a task or calculates a value (한가지의 작업이나 값을 계산하기 위해 쓰여짐)

=> function + function + function ... = program  
=> function = sub-program

### \* Function declaration

- function name(param1, param2) {body... return ;}
- one function === one thing (하나의 함수는 한가지의 일만 하도록 함)
- naming: doSomething, command, verb
- e.g. createCardAndPoint -> createCard, createPoint  
  (하나의 이름 안에 두가지의 기능이 있다면 세분화하는 방법 고민해보기)
- function is object in JS

### \* 형식

```js
function log(message){
  console.log(message);
}
log.('Hello@');
```

### \* 예시

```js
function printHello() {
	console.log("Hello");
}
printHello();
```

-> 실행화면 : Hello
