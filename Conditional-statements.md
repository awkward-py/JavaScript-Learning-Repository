Conditional statements in JavaScript allow you to control the flow of your program based on conditions. These conditions are expressed using logical expressions, and the program executes different blocks of code depending on whether the condition is true or false. Let's go through conditional statements step by step with examples using the name 'awkwardpy'.

### 1. **if Statement:**

The `if` statement is the most basic conditional statement. It executes a block of code if a specified condition is true.

```javascript
let userName = 'awkwardpy';

if (userName === 'awkwardpy') {
  console.log('Welcome, awkwardpy!');
} else {
  console.log('You are not awkwardpy.');
}
```

Explanation:
- We have a variable `userName` set to 'awkwardpy'.
- The `if` statement checks if `userName` is equal to 'awkwardpy'.
- If the condition is true, it executes the code inside the first block (the `console.log('Welcome, awkwardpy!')` statement).
- If the condition is false, it executes the code inside the `else` block.

### 2. **if-else Statement:**

The `if-else` statement extends the `if` statement by providing an alternative block of code to execute when the condition is false.

```javascript
let userName = 'awkwardpy';

if (userName === 'awkwardpy') {
  console.log('Welcome, awkwardpy!');
} else {
  console.log('You are not awkwardpy.');
}
```

Explanation:
- Same as the previous example, but the `else` block provides an alternative action when the condition is false.
- If `userName` is not 'awkwardpy', it executes the code inside the `else` block (`console.log('You are not awkwardpy.')`).

### 3. **if-else if-else Statement:**

The `if-else if-else` statement allows you to check multiple conditions in sequence.

```javascript
let userName = 'awkwardpy';
let userRole = 'admin';

if (userName === 'awkwardpy') {
  console.log('Welcome, awkwardpy!');
} else if (userRole === 'admin') {
  console.log('Hello, admin!');
} else {
  console.log('Access denied.');
}
```

Explanation:
- We introduce a new variable `userRole`.
- The first `if` condition checks if `userName` is 'awkwardpy'.
- If true, it executes the code inside the first block (`console.log('Welcome, awkwardpy!')`).
- If false, it checks the next condition (`else if (userRole === 'admin')`).
- If `userRole` is 'admin', it executes the code inside the second block (`console.log('Hello, admin!')`).
- If none of the conditions is true, it executes the code inside the `else` block (`console.log('Access denied.')`).

### 4. **Ternary Operator:**

The ternary operator is a shorthand way of writing a simple `if-else` statement.

```javascript
let userName = 'awkwardpy';
let greeting = userName === 'awkwardpy' ? 'Welcome, awkwardpy!' : 'You are not awkwardpy.';

console.log(greeting);
```

Explanation:
- The ternary operator `? :` takes a condition before the `?`.
- If the condition is true, it returns the value before the `:` (in this case, `'Welcome, awkwardpy!'`).
- If the condition is false, it returns the value after the `:` (in this case, `'You are not awkwardpy.'`).
- The result is stored in the variable `greeting` and then logged to the console.

Conditional statements are fundamental to programming and allow you to build logic into your code. They are used extensively to create dynamic and responsive programs.
