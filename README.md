# Unhandled Exception: Missing Request Body Fields in Express.js

This repository demonstrates a common error in Express.js applications: failing to handle missing fields in the request body.  When a POST request is made without the expected data, the application crashes due to an unhandled exception.

The `bug.js` file contains the erroneous code.  `bugSolution.js` provides a corrected version with comprehensive error handling.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install express`.
4. Run `node bug.js`.
5. Send a POST request to `http://localhost:3000/user` without a body, or with a body missing the 'name' field.

Observe the application crashing.

Then run `node bugSolution.js` and repeat the request, noting the improved error handling.