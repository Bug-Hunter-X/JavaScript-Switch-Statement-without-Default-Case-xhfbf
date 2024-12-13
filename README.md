# JavaScript Switch Statement without Default Case

This repository demonstrates a common error in JavaScript: using a switch statement without a default case.  The `calculate` function performs arithmetic operations based on the input operator. However, if an invalid operator is provided, it throws an error.  The solution demonstrates how to handle this scenario more gracefully by adding a default case.

## Bug

The original code lacks a `default` case in the `switch` statement within the `calculate` function.  This means if an unexpected operator is passed, an error is thrown.

## Solution

The solution adds a `default` case to the `switch` statement. This handles unexpected input by either returning a default value or logging an informative message, preventing unexpected errors.