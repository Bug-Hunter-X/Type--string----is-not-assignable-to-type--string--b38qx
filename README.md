# Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common TypeScript error: assigning an array of strings to a parameter expecting a single string.

## Bug
The `greeter` function expects a single string as input.  However, the `user` variable is an array of strings.  Calling `greeter(user)` results in a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array or changing the `user` variable to a single string.  The provided solution demonstrates the latter approach by accessing the first element of the array.