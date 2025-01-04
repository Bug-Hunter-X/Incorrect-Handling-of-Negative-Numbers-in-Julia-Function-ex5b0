# Julia Function Bug: Incorrect Handling of Negative Numbers

This repository demonstrates a bug in a simple Julia function that incorrectly handles negative numbers. The function is intended to square the input if it's positive and negate the square if it's negative. However, it produces unexpected results for negative inputs.

## Bug Description
The `myfunction` function in `bug.jl` fails to correctly handle negative numbers.  It returns the negative of the square instead of the square of the absolute value.

## Solution
The corrected function is found in `bugSolution.jl`. It uses the `abs()` function to ensure that only the absolute value is squared, leading to the correct output for all inputs.
