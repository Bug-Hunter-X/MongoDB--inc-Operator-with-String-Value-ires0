# MongoDB $inc Operator Error
This repository demonstrates an error that occurs when using the `$inc` operator in MongoDB update operations with a string value instead of a number.  The incorrect usage leads to unexpected behavior or errors. The solution provides the correct way to utilize the `$inc` operator.

## Bug
The bug lies in using a string value ("10") instead of a number (10) with the `$inc` operator. The `$inc` operator expects a numerical value to increment a field.  Attempting to increment with a string will result in a failure to update or unexpected behavior in MongoDB.