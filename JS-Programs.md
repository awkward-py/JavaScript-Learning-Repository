### 1. Simple Greeting Program:
```javascript
let userName = 'awkwardpy';

function greetUser(name) {
  return 'Hello, ' + name + '!';
}

let greeting = greetUser(userName);
console.log(greeting); // Output: Hello, awkwardpy!
```

### 2. Conditional Statement Program:
```javascript
let hour = 15;
let userName = 'awkwardpy';

if (hour < 12) {
  console.log('Good morning, ' + userName + '!');
} else {
  console.log('Good afternoon, ' + userName + '!');
}
```

### 3. Looping Program:
```javascript
let userName = 'awkwardpy';

for (let i = 0; i < 3; i++) {
  console.log('Iteration ' + (i + 1) + ': Hello, ' + userName + '!');
}
```

### 4. Array Program:
```javascript
let userName = 'awkwardpy';

let skills = ['JavaScript', 'React', 'Node.js'];

console.log('Skills of ' + userName + ':');
for (let i = 0; i < skills.length; i++) {
  console.log('- ' + skills[i]);
}
```

### 5. Object Program:
```javascript
let userName = 'awkwardpy';

let person = {
  name: userName,
  age: 25,
  isDeveloper: true,
};

console.log(person.name + ' is ' + person.age + ' years old.');
```

### 6. DOM Manipulation Program:
```javascript
let userName = 'awkwardpy';

// Assuming there's an HTML element with id="greeting"
let greetingElement = document.getElementById('greeting');
greetingElement.textContent = 'Hello, ' + userName + '!';
```

### 7. Asynchronous JavaScript Program (Using Promises):
```javascript
let userName = 'awkwardpy';

function fetchData() {
  return new Promise((resolve, reject) => {
    // Simulating an asynchronous operation
    setTimeout(() => {
      resolve('Data fetched successfully for ' + userName + '.');
    }, 2000);
  });
}

fetchData()
  .then((result) => {
    console.log(result);
  })
  .catch((error) => {
    console.error(error);
  });
