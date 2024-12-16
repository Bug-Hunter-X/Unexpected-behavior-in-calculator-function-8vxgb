# Unexpected Behavior in Calculator Function

This repository demonstrates an uncommon error in JavaScript related to exception handling within a simple calculator function. The calculator is designed to perform basic arithmetic operations (+, -, *, /), but it exhibits unexpected behavior when encountering invalid operations or division by zero.

## Bug Description

The `calculate` function throws an error when attempting to divide by zero, which is expected. However, it also throws an error for invalid operations, which might be unexpected depending on the design goals of the application.  The error messages lack specificity, and the use of a generic `Error` object makes debugging more challenging.

## Bug Solution

The provided solution enhances the error handling within the `calculate` function.  It provides more descriptive error messages, differentiating between 'division by zero' and 'invalid operation' errors, improving the user experience and ease of debugging.  

## How to reproduce

1. Clone the repository
2. Navigate to the repository directory
3. Open `bug.js` to view the erroneous code.
4. Run `bug.js` using node.js. Observe the unexpected behavior.
5. Open `bugSolution.js` to view the improved code.
6. Run `bugSolution.js` using node.js to see the improved error handling.