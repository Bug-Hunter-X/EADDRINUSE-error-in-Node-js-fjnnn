# Node.js EADDRINUSE Error

This repository demonstrates a common error encountered in Node.js development: the `EADDRINUSE` error, which occurs when a server attempts to bind to a port that is already in use.

The `bug.js` file contains the problematic code, while `bugSolution.js` provides a solution to handle this error gracefully.

## Reproducing the Error

1. Run `node bug.js`.
2. If successful, start a second instance of the server by running the command again.
3. Observe the `EADDRINUSE` error.