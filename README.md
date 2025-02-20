# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion with the '+' operator. When adding a number and a string, JavaScript implicitly converts the number to a string and performs string concatenation instead of numerical addition. This can lead to unexpected results.

## Bug Description

The `foo` function is intended to add two numbers. However, when called with a number and a string, it performs string concatenation, resulting in an unexpected output. 

## How to reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the code in a JavaScript environment (e.g., Node.js, browser console).

## Solution

The solution involves explicitly converting the operands to numbers before performing the addition, ensuring the correct numerical addition is performed. This is demonstrated in `bugSolution.js`
