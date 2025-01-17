# Unexpected String Concatenation in JavaScript
This repository demonstrates a common yet subtle bug in JavaScript stemming from its loose typing system.  When performing arithmetic operations with mixed data types (e.g., numbers and strings), JavaScript may implicitly convert the operands to strings resulting in unexpected string concatenation instead of numerical addition.

## The Bug
The `foo` function is intended to add two numbers. However, when called with a number and a string, it unexpectedly concatenates the number and the string.

## The Solution
The solution involves explicit type checking or conversion to ensure that the operation is performed on numerical data types.
