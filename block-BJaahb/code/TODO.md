Create the execution context diagram for the following code snippets:

```js
function outer() {
  let b = 10;
  function inner() {
    let a = 20;
    console.log(a + b);
  }
  return inner;
}
let getSum = outer();

let num = getSum();
```
<img width="549" alt="Screenshot 2022-01-26 at 9 51 06 PM" src="https://user-images.githubusercontent.com/86765712/151203004-a6d1db69-6b95-4887-a788-0ac7281dc825.png">

2.

Create the execution context diagram for following code. Also write the output of the code below.

```js
function getCounter() {
  let count = 0;

  return () => {
    return count++;
  };
}

let counter = getCounter();

counter(); // output
counter(); // output
counter(); // output
counter(); // output
```

3. Create the execution context diagram

```js
function makeColorChanger(color) {
  return function () {
    document.body.style.backgroundColor = color;
  };
}

let blue = makeColorChanger('blue');
let tomato = makeColorChanger('tomato');

blue();
tomato();
//tomato
// What will be the background color after the execution of last line
```
