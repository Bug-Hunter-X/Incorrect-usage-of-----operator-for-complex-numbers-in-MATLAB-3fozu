# Incorrect Usage of '^' Operator for Complex Numbers in MATLAB

This repository demonstrates a common error in MATLAB when using the '^' operator with complex numbers. The '^' operator does not handle complex numbers correctly in all cases, which can lead to unexpected results.  The example provided shows the correct way to compute the power of complex numbers using the element-wise power operator .^ 

## Problem

The provided MATLAB function `myFunction` attempts to calculate the square of a number. However, when using the `^` operator with complex numbers, the result is not always correct.

## Solution

The solution uses the element-wise power operator (`.^`) to correctly handle complex numbers.  This operator performs the calculation element-wise, ensuring the correct result for all inputs, including complex numbers. 