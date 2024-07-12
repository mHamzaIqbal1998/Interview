# JavaScript

[Best Reference For JS](https://www.w3schools.com/js/)
1. can we update keys or values of object/arrays declared with const?
2. create another object which has few of the keys from first object. i.e. const obj1 = { name:'abdul', age:26, email:'harpermanson' } -----> const obj2 = { age:'26',email:'harpermanson' }
3. [deep copy and shallow copy in js](https://www.javatpoint.com/shallow-copy-and-deep-copy-in-javascript#:~:text=ADVERTISEMENT-,In%20JavaScript%2C%20there%20are%20two%20ways%20to%20copy%20objects%3A%20shallow,and%20nested%20objects%20or%20arrays.)
4. pass by value and pass by reference
5. mutable vs immutable
6. high order function and its example
7. Closure
7. lexical scope
8. what is async/await and how is it different from promises
9. Self invoking functions
10. Event loop
11. Call Stack
12. Call back and Call back Hell
13. Promises and Promise Hell
14. How js work? which one it use compiler or interpreter
15. Generator functions
16. Event propagation and bubbling
17. Currying
18. Hoisting? The difference in the hoisting of var, let, const.
19. How are functions hoisted? Difference between hoisting of a function and hoisting of a variable assigned to a function.
20. Is JavaScript single-threaded or multi-threaded?
21. What are web APIs? How are web APIs handled with the event loop? When is the web APIs callback executed after the completion condition
22. How the stack operates in the case of synchronous and asynchronous functions
23. What is a callback queue?
24. MicroTasks
25. Difference between primitive and non-primitive data types.
26. What is the difference between the scope of var, let, and const
27. Differences between ES5 and ES6
28. Spread operator for copying objects and arrays vs Object.assign
29. What is the level till which spread operator deep copies?
30. Spread operator vs Rest Operator
31. Difference between Object.seal and Object.freeze
32. Differences between Array prototype methods e.g filter, map, reduce, etc.
33. Difference between foreach loop and array.map.
34. The difference between bind and apply and call
35. Concurrency and Parallelism In JavaScript
36. What will be the output of these codes
```js
for (let i = 5; i > 0; i--) {
  setTimeout(() => {
    console.log(i)
  }, i);
};
```

```js
 for (var i = 5; i > 0; i--) {
  setTimeout(() => {
    console.log(i)
  }, i);
};

```
why var and let behave different in this case? (hint scope difference)

```js
var x = 20

function printVal() {
  var x = 10
  console.log(x)
}
console.log(x)
printVal()
```

```js
function printVal() {
  let x = y = 10
  ++x
  return x
}

printVal()
console.log(y)
console.log(x)
```
