# Unhandled Promise Rejection in Express.js Server

This repository demonstrates a common error in Express.js applications: unhandled promise rejections.  Asynchronous operations within request handlers often lack proper error handling, which can lead to application instability.

The `bug.js` file showcases a server with an asynchronous operation that can throw an error. The error handling is incomplete, leading to an unhandled promise rejection.

The `bugSolution.js` file shows how to correctly handle this type of error to prevent unexpected crashes.