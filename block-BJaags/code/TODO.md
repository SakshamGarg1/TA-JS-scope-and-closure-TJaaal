To create the execution context diagram consider the following:

- Global and Function Execution Context
- Different Phases Of Execution Context
- Var let and const

Create the execution context diagram of the following code line by line.

```js

let num = 21;
function square(num) {
  return num * num;
}
let hundred = square(10);
console.log(hundred);
```<img width="632" alt="Screenshot 2022-01-22 at 9 37 01 PM" src="https://user-images.githubusercontent.com/86765712/150646363-07b10f31-4db3-47ad-b0fd-03f5face6f85.png">


Create the execution context diagram of the following code line by line.

```js
var num = 21;
function addFive(n) {
  return n + 5;
}
var five = addFive(0);
var ten = addFive(5);
console.log(five, ten);
```

Create the execution context diagram of the following code line by line.

```js
let marks = [34, 45, 56, 76];
function multiplyArrayByN(arr, n) {
  let finalArr = [];
  for (let elm of arr) {
    finalArr.push(elm * 2);
  }
  return finalArr;
}

let numbers = multiplyArrayByN(marks);
```
![Uploading Screenshot 2022-01-22 at 9.37.01 PM.png…]()
Create the execution context diagram of the following code line by line.

```js
counter();
function counter(){
  let count = 0;
  funciton increment(){
    return count++;
  }
  return increment()
}
```![Uploading Screenshot 2022-01-22 at 9.37.01 PM.png…]()

Create the execution context diagram of the following code line by line.

```js
counter();
let counter = function () {
  let count = 0;
  function increment() {
    return count++;
  }
  return increment();
};
```
