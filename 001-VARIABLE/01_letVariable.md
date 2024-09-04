# Variable Declaration Using `let`

A variable is a “**named storage**” for data. We can use variables to store,
manage, and manipulate data, making code more readable, reusable, and flexible.
To create a variable in JavaScript we use the `let` keyword.

- The `let` keyword was introduced in ES6 (2015)
- Variables declared with `let` have Block scope
- Variables declared with `let` must be Declared before use
- Variables declared with `let` cannot be Redeclare in the same scope
- Variables declared inside a `{ }` block cannot be accessed from outside the block

``` js
let message; // Declaring a variable named "message"
message = 'Hello'; // store the string 'Hello' in the variable named "message"
console.log(message); // shows the variable content
```

## Combine the variable declaration and assignment into a single-line

``` js
let message2 = 'World!'; // define the variable and assign the value
console.log(message2);
```

## Declaration of multiple variables in one line

``` js
let user = 'John',
    age = 25,
    message3 = 'Hello World!';

console.log(user);
console.log(age);
```

A single line per variable is suggested for better readability. The multiline variant is a bit longer but easier to read.

``` js
let user2 = 'John';
let age2 = 25;
```
