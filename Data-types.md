### 1. String:

Strings are sequences of characters enclosed in single or double quotes.

Example:
```javascript
let userName = 'awkwardpy';
```

Here, `userName` is a string variable storing the value 'awkwardpy'.

### 2. Number:

Numbers represent numeric values, including integers and floating-point numbers.

Example:
```javascript
let userAge = 25;
```

Here, `userAge` is a number variable storing the value 25.

### 3. Boolean:

Booleans represent true or false values.

Example:
```javascript
let isDeveloper = true;
```

Here, `isDeveloper` is a boolean variable set to `true`.

### 4. Undefined:

A variable is `undefined` if it is declared but not assigned any value.

Example:
```javascript
let jobTitle;
```

Here, `jobTitle` is declared but not assigned a value, so it is `undefined`.

### 5. Null:

`null` represents the intentional absence of any object value.

Example:
```javascript
let projectManager = null;
```

Here, `projectManager` is intentionally set to `null`.

### 6. Object:

Objects are complex data types, and they represent a collection of key-value pairs.

Example:
```javascript
let userDetails = {
  name: 'awkwardpy',
  age: 25,
  isDeveloper: true
};
```

Here, `userDetails` is an object containing name, age, and isDeveloper properties.

### 7. Array:

Arrays are ordered lists of values, and each value can be of any data type.

Example:
```javascript
let skills = ['JavaScript', 'React', 'Node.js'];
```

Here, `skills` is an array containing strings.

### 8. Symbol:

Symbols are unique and immutable primitive values, often used as property keys in objects.

Example:
```javascript
let uniqueKey = Symbol('uniqueKey');
```

Here, `uniqueKey` is a symbol with a unique description.

### 9. BigInt:

BigInt is a numeric data type that can represent integers of arbitrary precision.

Example:
```javascript
let bigNumber = 123456789012345678901234567890n;
```

Here, `bigNumber` is a BigInt.

### 10. Function:

Functions are a special type of object that can be invoked.

Example:
```javascript
function greetUser(name) {
  return 'Hello, ' + name + '!';
}

let greeting = greetUser('awkwardpy');
```

Here, `greetUser` is a function that returns a greeting based on the provided name.

JavaScript is a dynamically-typed language, meaning you don't need to explicitly declare the data type of a variable; it is determined at runtime. Understanding these data types is crucial for effectively working with JavaScript variables and creating robust applications.
