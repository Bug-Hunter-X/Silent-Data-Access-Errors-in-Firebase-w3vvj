# Silent Data Access Errors in Firebase

This repository demonstrates a common but easily overlooked issue in Firebase: the lack of explicit error handling when accessing nested properties within documents that do not exist.  Accessing a non-existent property can lead to crashes or unexpected behavior instead of a clear error message, making debugging challenging.

The `bug.js` file shows the problematic code, and `bugSolution.js` offers a robust solution involving explicit null checks and optional chaining.