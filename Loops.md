### `for` Loop:

#### Definition:
A `for` loop in JavaScript is used to repeatedly execute a block of code as long as a condition is true. It consists of three main parts: initialization, condition, and iteration expression.

#### Syntax:
```javascript
for (initialization; condition; iteration) {
  // code to be executed
}
```

### Example:

#### Code:
```javascript
let userName = 'awkwardpy';

for (let i = 0; i < 3; i++) {
  console.log('Iteration ' + (i + 1) + ': Hello, ' + userName + '!');
}
```

#### Step-by-Step Explanation:

1. **Initialization (`let i = 0;`):**
   - Declares and initializes the loop control variable `i` to 0.
  
2. **Condition (`i < 3;`):**
   - Checks if the condition `i < 3` is true.
   - If true, the loop continues; if false, the loop exits.

3. **Code Block (`console.log('Iteration ' + (i + 1) + ': Hello, ' + userName + '!');`):**
   - The code inside the loop block is executed.
   - `i + 1` is used to display the iteration number starting from 1.
   - Outputs a message: `Iteration 1: Hello, awkwardpy!`, `Iteration 2: Hello, awkwardpy!`, and `Iteration 3: Hello, awkwardpy!`.

4. **Iteration (`i++`):**
   - After executing the code block, the iteration expression is executed.
   - `i++` increments the value of `i` by 1.

5. **Back to Condition:**
   - The loop goes back to the condition. If `i < 3` is still true, the loop repeats; otherwise, it exits.

#### Output:
```
Iteration 1: Hello, awkwardpy!
Iteration 2: Hello, awkwardpy!
Iteration 3: Hello, awkwardpy!
```

This `for` loop runs three times, greeting "awkwardpy" in each iteration. You can customize the loop for different scenarios and conditions. Understanding how each part of the loop works is crucial for effective programming.
