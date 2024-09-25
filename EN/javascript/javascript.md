### 1. **Hoisting**

Hoisting is a built-in mechanism in JavaScript that moves variable declarations to the top of their scope (function or global). This process makes it seem like variables, functions, and classes are available at the beginning of the code, even if they are declared later.

---

### 2. **Scope**

Scope defines the section of code where certain variables and functions are accessible. It determines the visibility of these variables and functions. Variables and functions declared in a specific scope are not accessible outside of that scope.

---

### 3. **Difference Between `let` and `const`**

Both `let` and `const` are used to declare variables in JavaScript. The main difference is that variables declared with `const` cannot be reassigned once set, whereas `let` allows reassignment.

---

### 4. **Difference Between `let` and `var`**

Both `let` and `var` are used to declare variables. The key difference is that variables declared with `var` have function scope, whereas variables declared with `let` have block scope, meaning they are only accessible within the nearest set of curly braces `{}`.

---

### 5. **Primitive Data Types**

Primitive data types contain only values of a single type. Data types include:

- `Number`
- `String`
- `Boolean`
- `Null`
- `Undefined`
- `Symbol`
- `BigInt`

---

### 6. **DOM**

DOM stands for _Document Object Model_. The document object is a representation of an HTML document. It can be used to access and modify HTML content.

---

### 7. **Closure**

A closure is a mechanism that binds a function to its surrounding state. In practice, it allows an inner function to access the scope of an outer function.

---

### 8. **Difference Between `==` and `===`**

The `==` operator first performs type conversion and then compares both sides, so it returns `true` if the values are the same after casting to a common type.
The `===` operator does not perform type conversion, so to return `true`, both the type and the value need to match.

---

### 9. **Inheritance**

Inheritance is a feature in which one object gains access to the properties and methods of another object.

---

### 10. **Event Loop**

The event loop is a mechanism that allows JavaScript to handle multiple asynchronous events without blocking the execution of other tasks.

---

### 11. **IIFE (Immediately Invoked Function Expression)**

An IIFE is a function that is called immediately after its definition. It's wrapped in parentheses followed by more parentheses – this is to invoke the defined function.

`(() => console.log("Hello World"))();`

---

### 12. **Callback Hell**

Callback hell is a pattern consisting of many nested callback functions. It's considered an anti-pattern because the code is hard to read and modify.

---

### 13. **Promise**

A promise is an object that represents the completion (success or failure) of an asynchronous operation. After the asynchronous operation completes, its result can be handled by calling the `then` method on the promise.

---

### 14. **Async/Await**

`async` and `await` are related to promises. The `async` keyword before a function causes that function to return a promise. The `await` keyword can only appear inside an `async` function and causes the execution to pause until the promise is fulfilled.

---

### 15. **Currying**

Currying is a technique of transforming a function with multiple parameters like **f(a, b, c)** into **f(a)(b)(c)**. This breaks down a function into multiple functions each taking a single parameter.

---

### 16. **First-class Functions**

First-class functions are treated like ordinary variables. They can be assigned to another variable, passed as an argument to another function, and returned from another function.

---

### 17. **Function Statements vs Function Expressions**

A function statement is when a function is created using the `function` keyword, while a function expression assigns a function to a variable.

---

### 18. **First-order Functions**

First-order functions are functions that neither take other functions as arguments nor return functions.

---

### 19. **How to Find the Number of Parameters Expected by a Function**

We can use the `length` property of a function to find out the number of parameters it expects.

---

### 20. **How to Get the Type of a Variable**

We can use the `typeof` operator to find the type of a variable.

---

### 21. **Accessor Functions**

Accessor functions get or set the properties of an object. Setters use the `set` keyword, while getters use the `get` keyword.

---

### 22. **Anonymous Functions**

An anonymous function has no name. Anonymous functions can be assigned to variables or used as callbacks.

---

### 23. **Temporal Dead Zone**

The temporal dead zone is the area where variables declared with `let` and `const` reside. While variables have reserved memory space, they cannot be accessed until initialization.

---

### 24. **Memoization**

Memoization is a technique of caching computed results to improve function performance. Arguments provided to the function serve as keys in a cache object, which stores the result.

---

### 25. **Difference Between `async` and `defer`**

In `async`, the browser fetches the script asynchronously and executes it immediately, pausing HTML parsing. In `defer`, the script is executed only after HTML parsing is complete.

---

### 26. **Difference Between Local Storage and Session Storage**

Local storage persists data even after closing the browser, while session storage deletes data when the browser tab is closed.

---

### 27. **Difference Between `slice()` and `splice()`**

`slice()` returns a copy of a portion of the original array, whereas `splice()` modifies the array in place, allowing elements to be added or removed.

---

### 28. **Constructor Function**

A constructor function creates individual objects or groups of objects with similar properties and methods.

---

### 29. **The `Promise.race()` Function**

`Promise.race()` takes an array of promises and resolves or rejects with the instance of the promise that settles first.

---

### 30. **Methods: `call()`, `apply()`, and `bind()`**

- **`call()`**: Invokes a function with a specified context and parameters.
- **`apply()`**: Invokes a function with a specified context, but parameters are passed as an array.
- **`bind()`**: Returns a copy of the function with the specified context and preset arguments but does not invoke it immediately.

---

### 31. **Access Page History in JavaScript**

Use the `window.history` object to access the browser's history stack.

---

### 32. **Check if an Object is Frozen**

Use the `Object.isFrozen()` method to determine if an object is frozen.

---

### 33. **Handling Errors in JavaScript**

Use a `try-catch` block to handle errors. Code that may throw an error goes in the `try` block, and the error is handled in the `catch` block.

---

### 34. **Validate JSON in JavaScript**

The `JSON.parse()` function validates and parses JSON data. If valid, it converts the string into a JavaScript object; otherwise, it throws an error.

---

### 35. **JavaScript as a Dynamic Language**

JavaScript is a dynamic language, meaning variable types are determined at runtime.

---

### 36. **Arrow Functions**

Arrow functions provide a more concise syntax for writing functions. They don't have their own `this` and are not suitable for use as class constructors.

---

### 37. **Classes in JavaScript**

Classes, introduced in ES6, provide a way to create objects and use inheritance in JavaScript. They build on top of prototype-based inheritance.

---

### 38. **Cookies**

Cookies are small packets of data sent from the server to the client, stored in the browser, and sent back with every subsequent request.

---

### 39. **ES Modules**

ES modules, introduced in ES6, allow code to be split into reusable modules. JavaScript files can export functions or variables that can be imported by other files.

---

### 40. **Generator Functions**

A generator function is declared with `function*` and returns a generator object. It can pause execution using the `yield` keyword and resume later.

---

### 41. **Generators in JavaScript**

Generators are functions that use the `yield` keyword to pause and resume execution, making them useful for iterating over sequences or handling asynchronous operations.

---

### 42. **Higher-Order Functions**

Higher-order functions either accept other functions as arguments or return functions as results.

---

### 43. **Pure Functions**

Pure functions always produce the same output for the same input and do not have side effects.

---

### 44. **JavaScript Data Types**

Primitive data types: Number, String, Boolean, Null, Undefined, and Symbol. Non-primitive data type: Object.

---

### 45. **Three Types of JavaScript Errors**

- **Syntax Error**: Caused by incorrect syntax in the program.
- **Reference Error**: Occurs when trying to access a variable or function that isn't defined.
- **Type Error**: Occurs when a value is not of the expected type.

---

### 46. **What Does `delete` Do in JavaScript**

The `delete` operator is used to remove a property or key from an object.

---

### 47. **BOM (Browser Object Model)**

The Browser Object Model (BOM) allows interaction with the browser using the `window` object, the top-level object in the browser.

---

### 48. **Callback Functions**

A callback function is a function passed as an argument to another function and called inside the parent function to achieve a specific result.

---

### 49. **Strict Mode**

Strict mode, introduced in ECMAScript 5, enables stricter parsing and error handling. It is activated by including `"use strict";` at the top of a file or function.

---

### 50. **Unary Function**

A unary function is a function that accepts only one parameter.

---

### 51. **Event Delegation**

Event delegation allows efficient event handling by adding a single event listener to a parent element rather than to each child element individually. It uses the `event.target` property to respond to events on specific elements.

---

### 52. **Debouncing**

Debouncing ensures that a function is called only after a specified period of inactivity. This is useful for limiting function calls in response to user input, such as search queries.

---

### 53. **Event Handling**

Event handling refers to managing events like `click` or `keypress` triggered by user interaction on a webpage.

---

### 54. **Constructor Functions**

A constructor function is a function used to create and initialize objects. The `this` keyword inside the constructor refers to the new object being created.

---

### 55. **What is JSON**

JSON stands for JavaScript Object Notation, a lightweight format for storing and exchanging data, similar to JavaScript objects.

---

### 56. **What is `NaN` in JavaScript**

`NaN` stands for "Not a Number" and represents an invalid number in JavaScript.

---

### 57. **Object Destructuring**

Destructuring allows you to extract properties from objects or arrays and assign them to variables.

---

### 58. **Reflection in JavaScript**

Reflection is the ability of an object to inspect and manipulate its properties and methods.

---

### 59. **Arguments Object**

The arguments object is an array-like object that contains the arguments passed to a function.

---

### 60. **Mutable vs Immutable Objects**

Mutable objects can have their properties modified after creation, while immutable objects cannot be changed once created.

---

### 61. **Difference Between `window` and `document` Objects**

- **`window`**: The `window` object represents the browser window and is the top-level object of the BOM.
- **`document`**: The `document` object represents the content loaded in the browser window, typically the HTML document.

---

### 62. **Difference Between `fetch()` and `XMLHttpRequest()`**

`fetch()` is a modern, promise-based API for making HTTP requests, while `XMLHttpRequest()` is an older API for achieving the same purpose but with a different approach to handling asynchronous operations.

---

### 63. **Difference Between Functions and Methods**

Functions are independent blocks of code, while methods are functions that are properties of an object.

---

### 64. **Prototypal vs Classical Inheritance**

Prototypal inheritance allows objects to inherit directly from other objects. Classical inheritance uses classes that inherit from other classes.

---

### 65. **Difference Between `null` and `undefined`**

`null` is an assigned value representing "no value," while `undefined` means a variable has been declared but has not yet been assigned a value.

---

### 66. **`unshift()` Method**

The `unshift()` method adds new elements to the beginning of an array and returns the new length of the array.

---

### 67. **Use of `this` in JavaScript**

`this` refers to the object to which the function belongs. In constructors, `this` is used to refer to the newly created object.

---

### 68. **Throttling**

Throttling limits the number of times a function is called within a certain timeframe.

---

### 69. **Why We Need Modules**

Modules help organize code by splitting it into smaller, reusable components, making collaboration easier and improving maintainability in large projects.
