# Unhandled Null or Undefined Values in Function Arguments

This repository demonstrates a common JavaScript error caused by unhandled null or undefined values passed as arguments to a function.

## The Bug

The `bug.js` file contains a function that doesn't explicitly check for null or undefined values in its arguments.  When these values are passed, it can lead to unexpected behavior or errors.

## The Solution

The `bugSolution.js` file demonstrates a solution that explicitly checks for null or undefined values and handles them appropriately, preventing unexpected outcomes.

## How to reproduce the bug:
1. Clone the repository.
2. Open `bug.js` in your preferred code editor.
3. Run the code with null or undefined values passed as arguments to the `foo` function.

## How to use the solution:
1. Open `bugSolution.js` in your preferred code editor.
2. Observe how the code gracefully handles null or undefined values.