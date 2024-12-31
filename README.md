# MongoDB $inc Operator Error
This example demonstrates an incorrect use of the MongoDB `$inc` operator within an update query. The `$inc` operator is designed to increment a numerical field by a specified value.  Using a string instead will result in an error and prevent the update from being applied. This example showcases the issue and provides a solution.

## Bug
The file `bug.js` demonstrates the incorrect usage of the `$inc` operator. The update fails due to the string value passed to `$inc`. 

## Solution
The `bugSolution.js` shows the correct usage of `$inc`, providing a numerical value for incrementing the field.