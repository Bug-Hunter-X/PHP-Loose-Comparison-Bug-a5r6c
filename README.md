# PHP Loose Comparison Bug

This example demonstrates a common error in PHP caused by loose comparison using the '==' operator.  Loose comparison does not check if the types of variables are the same before comparing values.  This can result in unexpected behavior and bugs that are difficult to track down.

The `bug.php` file contains the buggy code. The `bugSolution.php` file shows how to fix it using strict comparison.

## How to reproduce

1. Run `bug.php`.
2. Observe the unexpected true results when comparing different types.

## Solution

Always use the strict comparison operator '===' in PHP to ensure that both the value and type of variables match. The solution is demonstrated in `bugSolution.php`.