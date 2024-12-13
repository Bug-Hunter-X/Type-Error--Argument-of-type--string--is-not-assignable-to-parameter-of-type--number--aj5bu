# TypeScript Type Error Bug

This repository demonstrates a common type error in TypeScript that occurs when passing arguments of the wrong type to a function.

## Bug Description

The `add` function is defined to accept two numbers and return their sum.  However, in the example, the function is called with a string as the second argument. TypeScript's type system correctly catches this error at compile time.

## Bug Solution

The solution involves ensuring that only numbers are passed to the `add` function.  This can be done via type guards or input validation.