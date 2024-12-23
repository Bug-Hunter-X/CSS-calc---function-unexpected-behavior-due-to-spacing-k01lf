# CSS calc() Function Spacing Issue

This repository demonstrates a subtle but important error in using the CSS `calc()` function.  Spaces within the `calc()` function's arguments can unexpectedly prevent correct calculation.

## The Problem

The `calc()` function is a powerful tool for dynamic calculations within CSS. However, including spaces between operators and values within the calculation can lead to unexpected results or even total failure of the function.

## The Solution

The solution is simple: Ensure that there are no spaces between the operators (+, -, *, /) and their adjacent numeric values or percentages within the `calc()` function.

## Files

* `bug.css`: Demonstrates the incorrect usage of spaces in the `calc()` function.
* `bugSolution.css`: Shows the corrected usage with no spaces between operators and values.