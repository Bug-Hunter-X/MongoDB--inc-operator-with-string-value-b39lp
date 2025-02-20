# MongoDB $inc operator with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB updates: attempting to increment a field by a string value.

The `bug.js` file shows the incorrect usage, leading to unexpected behavior or errors. The `bugSolution.js` file provides the correct solution.

## Bug
The `$inc` operator expects a numerical value (integer or double) to increment. Using a string instead will result in an error or unexpected results.  The correct usage is shown in `bugSolution.js`.