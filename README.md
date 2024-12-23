# MongoDB $inc operator error
This example demonstrates an incorrect usage of MongoDB's `$inc` operator, which results in an error. The `$inc` operator is used to increment a numeric field by a specified value. When using strings instead of numbers, it will fail.

## Bug
The bug lies in the incorrect usage of the `$inc` operator with a string value instead of a number. This causes an error during the update operation.

## Solution
The solution involves ensuring that the value used with the `$inc` operator is a number, not a string. This corrects the update operation.