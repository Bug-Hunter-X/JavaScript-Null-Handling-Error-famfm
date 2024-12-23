# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript: not explicitly handling null or undefined values. The `bug.js` file contains a function that attempts to add two numbers but doesn't check for null or undefined inputs, which can lead to unexpected results or crashes. The `bugSolution.js` file provides a corrected version that properly handles null values, demonstrating best practices for avoiding this type of error. 

## How to Reproduce

1. Clone this repository.
2. Run `bug.js` using a JavaScript environment (e.g., Node.js). Observe the incorrect behavior when null values are passed as input.
3. Run `bugSolution.js`. Observe that it produces the expected outputs.