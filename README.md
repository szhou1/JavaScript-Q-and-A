# JavaScript-Q-and-A

## Events
- [ ] Explain event delegation.
- [ ] Describe event bubbling.
- [ ] Describe event capturing.

## Browser
- [ ] Explain the same-origin policy with regards to JavaScript.

## Language
- [ ] Explain how `this` works in JavaScript.
  * `this` refers to the current context. Within a function, the context will be the object of the to the left of the dot during function invocation.
- [ ] How has `this` changed in ES6?
- [ ] Explain prototypal inheritance.
- [ ] What is a closure, and how/why would you use one?
- [ ] What language constructions do you use for iterating over object properties and array items?
- [ ] Can you describe the main difference between the Array.forEach() loop and Array.map() methods and why you would pick one versus the other?
- [ ] What's a typical use case for anonymous functions?
- [ ] What's the difference between host objects and native objects?
- [x] What does the new keyword do?
  * It creates an object
  * It sets __proto__ / constructor of the newly created object to link to the prototype property of the parent function/object combo
  * It sets the context of the old object to the this context of the newly created object
  * It returns `this` if there’s nothing returned from the called function / object
- [ ] Explain the difference between: function Person(){}, var person = Person(), and var person = new Person()?
- [ ] Explain the differences on the usage of foo between function foo() {} and var foo = function() {}
- [ ] Can you explain what Function.call and Function.apply do? What's the notable difference between the two?
- [x] Explain Function.prototype.bind.
  * Bind will return a new function / object with the context set to the first parameter
- [ ] A bound function cannot be re-bound. Its context can only change with the new keyword
- [ ] What's the difference between feature detection, feature inference, and using the UA string?
- [ ] Explain "hoisting".
- [ ] What's the difference between an "attribute" and a "property"?
- [ ] What are the pros and cons of extending built-in JavaScript objects?
- [ ] What is the difference between == and ===?
- [ ] Why is it called a Ternary operator, what does the word "Ternary" indicate?
- [ ] What is strict mode? What are some of the advantages/disadvantages of using it?
- [ ] What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
- [ ] What tools and techniques do you use debugging JavaScript code?
- [ ] Explain the difference between mutable and immutable objects.
  - [ ] What is an example of an immutable object in JavaScript?
  - [ ] What are the pros and cons of immutability?
  - [ ] How can you achieve immutability in your own code?
- [ ] Explain the difference between synchronous and asynchronous functions.
- [ ] What is event loop?
- [ ] What is the difference between call stack and task queue?
- [ ] What is the definition of a higher-order function?

# ES2015
- [ ] What are the differences between variables created using let, var or const?
- [ ] What are the differences between ES6 class and ES5 function constructors?
- [ ] Can you offer a use case for the new arrow => function syntax?
  - [ ] How does this new syntax differ from other functions?
- [ ] What advantage is there for using the arrow syntax for a method in a constructor?
- [ ] Can you give an example for destructuring an object or an array?
- [ ] Can you give an example of generating a string with ES6 Template Literals?
- [ ] Can you give an example of a curry function and why this syntax offers an advantage?
- [ ] What are the benefits of using spread syntax and how is it different from rest syntax?
- [ ] Why you might want to create static class members?

## Misc
- [ ] What's the difference between a variable that is: null, undefined or undeclared?
  - [ ] How would you go about checking for any of these states?
- [ ] How can you share code between files?

