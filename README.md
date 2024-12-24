# JavaScript Error Handling: Division by Zero

This repository demonstrates a common error in JavaScript: forgetting to handle the potential error of dividing by zero. The provided `bug.js` file contains a `calculator` object with functions for basic arithmetic. The `divide` function throws an error if the divisor is 0. However, this error isn't handled. `bugSolution.js` provides a solution using a `try...catch` block to handle the error gracefully.

## How to Run

1. Clone this repository.
2. Open the files (`bug.js` and `bugSolution.js`) in a JavaScript environment (browser's console, Node.js, etc.).
3. Execute the code in each file.  Observe the different behavior between the unhandled and handled error scenarios.

## Learning Points

- Importance of error handling in JavaScript to prevent unexpected program termination.
- Effective use of `try...catch` blocks to catch and handle exceptions.
- The `throw new Error()` method for creating custom error objects.