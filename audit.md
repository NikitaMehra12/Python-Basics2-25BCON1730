# README Audit

## README Fact-Check Table

| Claim Made in README                               | True?        | Evidence / Correction Made                                                          |
| -------------------------------------------------- | ------------ | ----------------------------------------------------------------------------------- |
| Program generates the Fibonacci sequence           | Yes          | The program calculates Fibonacci numbers using the sum of the previous two numbers. |
| Program generates 10 Fibonacci terms               | Yes          | `n = 10` sets the loop to run 10 times.                                             |
| Program accepts input from the terminal            | No           | There is no `input()` function. Claim deleted.                                      |
| Program allows users to choose the number of terms | No           | The value of `n` is fixed at `10`. Claim corrected.                                 |
| Program prints the Fibonacci sequence on one line  | Yes          | `print(a, end=" ")` prints numbers on the same line.                                |
| Program starts with `0` and `1`                    | Yes          | The variables `a = 0` and `b = 1` initialize the sequence.                          |
| Program uses a loop                                | Yes          | `for i in range(n)` repeats the calculation 10 times.                               |
| Program calculates the next term by addition       | Yes          | `next = a + b` adds the previous two numbers.                                       |
| Program validates user input                       | No           | There is no input or validation logic. Claim deleted.                               |
| Program handles errors                             | No           | No error-handling logic is implemented. Claim deleted.                              |
| Python 3 is required                               | Yes          | The program is a Python script that can be executed using Python 3.                 |
| Program uses external libraries                    | No           | No external libraries are imported.                                                 |
| Program requires `requirements.txt`                | No           | No external dependencies are needed. Installation instruction removed.              |
| Program outputs `0 1 1 2 3 5 8 13 21 34`           | Yes          | The code prints the first 10 Fibonacci terms.                                       |
| Time complexity is O(n)                            | Yes          | The loop executes `n` times, with constant-time operations per iteration.           |
| Space complexity is O(1)                           | Yes          | The program uses a fixed number of variables.                                       |
| Project uses an MIT License                        | Not verified | A `LICENSE` file must exist to confirm the project's licensing terms.               |
