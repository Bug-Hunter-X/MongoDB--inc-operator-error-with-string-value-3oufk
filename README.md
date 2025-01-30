# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value. However, if a string value is provided, it results in an error.

## Bug
The bug is caused by providing a string value ('abc') to the `$inc` operator. The correct usage requires a numerical value.

## Solution
The solution is to provide a numerical value to the `$inc` operator. This corrects the operation and updates the field as intended.

## How to reproduce
1. Create a MongoDB collection with a numerical field.
2. Use the incorrect code to update the collection.
3. Observe the error or unexpected result.