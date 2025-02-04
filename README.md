# MongoDB $inc operator error
This example demonstrates an incorrect usage of the $inc operator in MongoDB, resulting in an error. The solution demonstrates the correct way to use the operator.
## Bug
The bug lies in the usage of the `$inc` operator. The value to increment must be a number, and using a string will result in an error.
## Solution
The solution corrects this error by providing a numeric value to the `$inc` operator. This change will allow the update operation to execute correctly.