## JS INTERVIEW QUESTION

### 1. Why do we use JavaScript and its advantages?

- JavaScript is a programming language used to add interactivity and dynamic behavior to websites. Its advantages include being versatile, supporting both front-end and back-end development, having a large ecosystem of libraries, and enabling asynchronous operations for smoother user experiences.

### 2. Difference between == and ===?

- `==` is a loose equality operator that performs type coercion, allowing different data types to be compared. `===` is a strict equality operator that checks both value and type, ensuring a more accurate comparison.

### 3. Difference between Null and undefined?

- `null` is a deliberate absence of any object value, while undefined represents an uninitialized or non-existent variable.

### 4. What is NaN in JavaScript?

`NaN` stands for "Not a Number" and is a special value returned when a mathematical operation results in an undefined or unrepresentable value.

### 5. Difference between Var, let, and const?

- `var` has function-scoping, `let` has block-scoping, and `const` is like let but the variable cannot be reassigned once declared.

### 6. What is Hoisting in JavaScript?

- Hoisting is the JavaScript behavior where variable and function declarations are moved to the top of their containing scope during the compilation phase.

### 7. What is the Lexical Environment?

- The lexical environment is a concept that includes the association of identifiers with their values and the reference to the outer lexical environment, forming a hierarchical structure.

### 8. What is the Temporal Dead Zone?

- The Temporal Dead Zone is the period between entering a scope and the actual variable declaration, during which accessing the variable results in a ReferenceError.

### 9 . Different types of loops? Var and let in for loop?

- Loops include `for`, `while`, and `do-while`. Using var in a for loop may lead to variable leakage, whereas let is block-scoped and avoids this issue.

### 10 . What is the This Keyword in JavaScript? Why do we use it?

- `this` refers to the object it belongs to. It is used to access or modify the object's properties and methods and is determined by how a function is called.

### 11 . What is an API? How to fetch data from an API?

- An `API` (Application Programming Interface) is a set of rules allowing different software applications to communicate. Fetching data involves using the fetch function in JavaScript to make HTTP requests to an API and handle the returned data.

### 12. Difference between SetTimeout and SetInterval? Is it synchronous or asynchronous? Is it a part of JavaScript?

- `setTimeout` executes a function once after a specified delay, while `setInterval` repeatedly executes a function at defined intervals. Both are asynchronous and are part of JavaScript.

### 13. What are Event loops? Explain the whole flow.

- Event loops manage the execution of code, handling asynchronous tasks by putting them in a queue and executing them when the call stack is empty, ensuring non-blocking operations.

### 14. What is Call Stack?

- The call stack is a data structure that records function calls during the execution of a program. It follows the Last In, First Out (LIFO) principle.

### 15. What is a micro task queue? Difference between Micro and Macro Stack?

- The micro task queue holds tasks with higher priority than the macro task queue. Micro tasks are executed before the next cycle of the event loop, while macro tasks are scheduled for future cycles.

### 16. What is Callback hell? What is the inversion of control? What is a pyramid of Dom?

- Callback hell is a situation where nested callbacks make code hard to read. Inversion of control is a design principle where control flow is inverted, often seen in callback-based code. A pyramid of DOM refers to deeply nested structures in the Document Object Model.

### 17. How to avoid callback hell?

- To avoid callback hell, use named functions, modularize code, and embrace modern JavaScript features like Promises or async/await.

### 18. What are Promises? Drawbacks of Promises? Methods of Promises? State of Promises?

- Promises are objects representing the eventual completion or failure of an asynchronous operation. Drawbacks include lack of cancellation and error handling. Methods include then, catch, and finally. States are `pending`, `fulfilled`, or `rejected`.

### 19. What is Async Await? Is it synchronous or asynchronous?

- Async/await is a syntax for handling asynchronous operations. It allows writing asynchronous code in a more synchronous style, making it easier to read. It is inherently asynchronous.

### 20. Can async/await and .then and .catch be used together?

- Yes, async/await and .then/.catch can be used together, but mixing them should be done with caution to maintain code readability and avoid potential issues.

### 21. Difference between Rest operator or Spread Operator?

- The rest operator (...) is used in function parameters to collect remaining arguments into an array, while the spread operator is used to spread elements of an array or object into another array or object.

### 22. What is the difference between Call, Apply, and Bind?

- `call` and `apply` are used to invoke a function with a specified this value, while bind creates a new function with a permanently bound this value.

### 23. What is closure? Lexical Scope? What is currying?

- A closure is a function that retains access to variables from its outer (enclosing) scope. Lexical scope refers to the scope determined by the placement of variables in the code. Currying is a technique of transforming a function with multiple arguments into a series of functions with a single argument.

### 24. What is a class and object? What are Prototypes?

- A class is a blueprint for creating objects, and an object is an instance of a class. Prototypes allow objects to inherit properties and methods from other objects.

### 25. Difference between SessionStorage and localStorage?

- `sessionStorage` stores data for the duration of a page session, while `localStorage` stores data with no expiration time, allowing it to persist across sessions.

### 26. Difference between map and forEach.

- `map` creates a new array with the results of calling a provided function on every element, while `forEach` executes a provided function once for each array element, but it doesn't create a new array.

### 27. How to Handle Error in JavaScript? .then and .catch and Try? Is .then synchronous or asynchronous?

- Errors can be handled using try-catch blocks for synchronous code and using `.catch` for Promises. `.then` and `.catch` are asynchronous, and `try-catch` is synchronous.

### 28. Difference between Promise.all and Promise.allSettled.

- `Promise.all` resolves when all promises in the iterable resolve, whereas `Promise.allSettled` waits for all promises to settle (either resolve or reject).

### 30. Reconciliation

- React Reconciliation is the process through which React updates the Browser DOM. It makes the DOM updates faster in React. It updates the virtual DOM first and then uses the diffing algorithm to make efficient and optimized updates in the Real DOM.




