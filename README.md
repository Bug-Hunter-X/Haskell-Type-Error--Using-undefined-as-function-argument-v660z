# Haskell Type Error: Using 'undefined' as a Function Argument

This repository demonstrates a common error in Haskell: passing the `undefined` value to a function that expects a specific type.  The code attempts to use `undefined` as an argument to a function that expects an `Int`. This results in a type error because `undefined` has no concrete type and therefore cannot satisfy the function's type signature.

## How to Reproduce

1. Clone this repository.
2. Compile and run `bug.hs` using a Haskell compiler (GHC).  You will see a type error. 

## Solution

The solution is to avoid passing `undefined` to functions that expect a concrete type.   Proper error handling or default values should be used instead.  Refer to `bugSolution.hs` for a corrected version of the code.
