# Incorrect Usage of $inc Operator in MongoDB
This repository demonstrates a common error when using the `$inc` operator in MongoDB. The `$inc` operator is used to increment a numerical field by a specified value. However, if the field does not exist or is not a number, then the `$inc` operator will not work correctly. This can lead to errors in your application.

## Bug
The bug is that the `$inc` operator is used incorrectly. It is used to increment a field that does not exist, or that is not a number.

## Solution
The solution is to use the correct syntax for the `$inc` operator. The `$inc` operator must be used with a numerical field. If the field does not exist, then it will be created. If the field is not a number, then an error will be thrown.