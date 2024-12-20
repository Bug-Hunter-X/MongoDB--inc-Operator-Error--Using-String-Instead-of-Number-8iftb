# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numeric field by a specified value.  However, using a string instead of a number will result in unexpected behavior or an error.

## Bug Description

The provided code attempts to increment the `field` using a string value ('1'). This is incorrect and will lead to the update operation failing to correctly modify the field.

## Solution

The solution demonstrates the correct usage of the `$inc` operator using a numeric value.