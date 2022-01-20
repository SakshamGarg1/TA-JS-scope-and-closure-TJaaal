1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let marks = function(marks, total) {
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// let percentage = function(marks, total) {
  return (marks * 100) / total;
}
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```
```js
let percentage = (marks, total)=> {
  return (marks * 100) / total;
};
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

```js
let percentage = (marks, total) => (marks * 100) / total;
```
```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
```js
because by the expression we actualy define the function 
eg 
function percentage(marks, total) {
  return (marks * 100) / total;
};

now expression
let percentage = (marks, total) => (marks * 100) / total;
```
4. Why is a function call an expression in JavaScript?
because we express the changes in the DOM 


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // undefined
five = add; //  valid return a +b
five = five(10, 11); // Answer 21
five = function () {
  return 'Hello';
}; // Answer'hello'
```

6. What is the difference between function definition and function call? Explain with an example.

7. What is the similarities between function definition and function call?

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}//undefined

hello.user = 'Sam'; // valid or invalid
valid
```

9. What is higher order function explain with an example.

10. Explain what is callback function. Why you can pass a function inside a function?
