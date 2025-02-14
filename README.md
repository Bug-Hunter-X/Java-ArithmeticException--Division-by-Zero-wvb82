# Java ArithmeticException: Division by Zero

This repository demonstrates a common Java error: the `ArithmeticException` caused by division by zero.  The `Bug.java` file contains the faulty code, while `BugSolution.java` provides a corrected version.

The error is explained in detail, along with a solution that incorporates robust error handling to prevent the exception from occurring.

## Bug Description
The original code attempts to divide an integer by zero, which is undefined in mathematics and results in an `ArithmeticException` at runtime. This is a common and easily preventable mistake. 

## Solution
The solution involves adding a check to ensure the divisor is not zero before performing the division. If the divisor is zero, an alternative action (like displaying an error message or returning a default value) is taken.