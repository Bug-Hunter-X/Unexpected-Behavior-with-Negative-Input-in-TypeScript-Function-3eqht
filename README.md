# Unexpected Behavior with Negative Input in TypeScript Function

This repository demonstrates an unexpected behavior in a simple TypeScript function that handles number printing. When a negative number is passed as input, the function doesn't throw an error or provide an appropriate message, which can lead to unexpected behavior in the application. 

## Bug Description

The `printNumbers` function is intended to print numbers from 1 to `n`. However, when a negative number is provided as input, it silently does nothing instead of throwing an error or gracefully handling the negative input. This is unexpected and can lead to bugs that are difficult to trace.

## Bug Solution

The provided solution addresses this issue by adding input validation and throwing an error when a negative number is passed as an argument.  This ensures that the function's behavior is predictable and helps prevent unexpected results.