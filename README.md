# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js servers: unresponsiveness caused by long-running synchronous operations that block the event loop.  The `server.js` file contains a flawed server implementation. The `serverSolution.js` provides a corrected version using asynchronous operations.