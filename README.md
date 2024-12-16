# PHP Function Call Without Parentheses

This repository demonstrates a common error in PHP where a function is called without parentheses, leading to unexpected behavior or parse errors.

The file `bug.php` contains the erroneous code. The file `bugSolution.php` shows the corrected version.

## Bug

In PHP, a function call requires parentheses even if the function takes no arguments.  Attempting to call a function without parentheses may cause a parse error or, less obviously, simply return the function's definition instead of executing it.

## Solution

Always ensure that you use parentheses when calling a function in PHP, even if the function takes no arguments. This ensures that the function is executed correctly.