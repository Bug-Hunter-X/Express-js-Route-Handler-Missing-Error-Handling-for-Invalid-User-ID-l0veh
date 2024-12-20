# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling when dealing with user input.  Specifically, the code attempts to parse a user ID as an integer without checking if the input is valid. This can lead to unexpected behavior or crashes if the ID is not an integer.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version with robust error handling.