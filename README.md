# JavaScript Function Argument Null Check Error

This repository demonstrates a common error in JavaScript: neglecting to properly handle null values as function arguments.  The `bug.js` file contains code with this error, while `bugSolution.js` shows the corrected version.

**The Problem:**

The original function `foo` does not explicitly check for `null` arguments. This can lead to unexpected behavior, errors, or incorrect results.

**The Solution:**

The solution in `bugSolution.js` adds robust null checks using the strict equality operator (`===`) to explicitly handle null values. This prevents potential issues and makes the function more robust.

This example highlights the importance of thorough input validation in JavaScript functions to avoid unexpected errors and ensure code reliability.