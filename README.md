# F# Recursive Factorial Bug

This repository demonstrates a common error in recursive functions in F#: the infamous StackOverflowException. The `factorialBug.fs` file contains a recursive factorial function that does not handle negative input correctly, leading to infinite recursion and the exception. The solution, provided in `factorialSolution.fs`, adds input validation to prevent this error.