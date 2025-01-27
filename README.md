# Unhandled Division by Zero Error in TypeScript

This repository demonstrates a common error in TypeScript: unhandled division by zero. The `bug.ts` file contains a function that throws an error when dividing by zero, but the error isn't handled properly, causing the application to crash. The `bugSolution.ts` file shows how to handle the error properly using a try-catch block.

## Bug

The `bug.ts` file contains a function that divides two numbers.  If the second number (the divisor) is zero, the function throws an error. However, this error is not caught, leading to a crash.

## Solution

The `bugSolution.ts` file provides a solution by using a `try-catch` block to handle the potential `Error`. This prevents the application from crashing and allows for graceful error handling.

## How to run

1. Clone this repository.
2. Navigate to the repository directory.
3. Compile and run the code using the TypeScript compiler: `tsc bug.ts && node bug.js` and `tsc bugSolution.ts && node bugSolution.js`

Observe the differences in behavior between the unhandled error in `bug.ts` and the handled error in `bugSolution.ts`.