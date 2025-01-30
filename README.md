# Inconsistent Spacing in CSS `calc()` Expressions

This repository demonstrates a common error in CSS: inconsistent spacing within `calc()` expressions.  Incorrect spacing can lead to unexpected results or parsing errors. The `bug.css` file shows an example of incorrect spacing, while `bugSolution.css` provides the correct solution.

## Bug

The `bug.css` file shows an example of the error: Missing spaces around the minus operator.  This often leads to CSS parsers failing to recognize and process the expression correctly. 

## Solution

The `bugSolution.css` file demonstrates how to correctly write `calc()` expressions.  Always ensure there's a space before and after each operator (+, -, *, /).