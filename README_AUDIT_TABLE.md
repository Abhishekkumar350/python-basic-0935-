# README Audit

This audit verifies the factual claims made in `README.md` against the actual Python programs in the repository.

| #  | Claim made in README                                             | True?       | Evidence / Verification                                                                                                                                  |
| -- | ---------------------------------------------------------------- | ----------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | The repository contains six basic Python programs.               | Yes         | Six programs are documented for this HW-05 submission: factorial, Fibonacci, Student Structure, largest number, smallest number, and sum of two numbers. |
| 2  | `factorial.py` calculates the factorial of 5.                    | Yes         | The program sets `n = 5` and calculates the factorial using a `for` loop.                                                                                |
| 3  | `factorial.py` uses an iterative loop.                           | Yes         | The program uses `for i in range(1, n + 1)`.                                                                                                             |
| 4  | `fibonacci_and_structure.py` takes the number of terms as input. | Yes         | The program uses `input()` and converts the value to an integer.                                                                                         |
| 5  | `fibonacci_and_structure.py` generates a Fibonacci series.       | Yes         | The program initializes `t1 = 0` and `t2 = 1` and calculates subsequent terms.                                                                           |
| 6  | `fibonacci_and_structure.py` contains a Student class.           | Yes         | A `Student` class is defined in the program.                                                                                                             |
| 7  | The Student class stores name, roll number, and average marks.   | Yes         | The constructor stores `name`, `rollNo`, and `avgMarks` as instance attributes.                                                                          |
| 8  | The student is named Rahul.                                      | Yes         | The program creates `Student("Rahul", 101, 85.5)`.                                                                                                       |
| 9  | The student's roll number is 101.                                | Yes         | The program creates the student with roll number `101`.                                                                                                  |
| 10 | The student's average marks are 85.5.                            | Yes         | The program creates the student with `avgMarks = 85.5`.                                                                                                  |
| 11 | `largest_number.py` takes three numbers as input.                | Yes         | The program uses three `input()` statements for `n1`, `n2`, and `n3`.                                                                                    |
| 12 | `largest_number.py` finds the largest number.                    | Yes         | Conditional comparisons determine which of the three values is largest.                                                                                  |
| 13 | `smallest_number.py` compares three numbers.                     | Yes         | The program defines `a = 15`, `b = 7`, and `c = 22`.                                                                                                     |
| 14 | `smallest_number.py` finds the smallest number.                  | Yes         | Conditional statements compare the three values and assign the smallest value.                                                                           |
| 15 | The current smallest-number values are 15, 7, and 22.            | Yes         | These values are directly assigned to `a`, `b`, and `c`.                                                                                                 |
| 16 | `sum_2_numbers.py` takes two numbers as input.                   | Yes         | The program takes input for `num1` and `num2`.                                                                                                           |
| 17 | The two inputs are converted to floating-point numbers.          | Yes         | Both inputs use `float(input(...))`.                                                                                                                     |
| 18 | `sum_2_numbers.py` calculates their sum.                         | Yes         | The program calculates `total_sum = num1 + num2`.                                                                                                        |
| 19 | The programs use basic Python functionality.                     | Yes         | The provided programs use variables, input/output, loops, conditionals, and a class.                                                                     |
| 20 | External Python packages are required.                           | No          | No external package imports are present in the provided programs.                                                                                        |
| 21 | A `requirements.txt` file is needed.                             | No          | The programs do not use external packages, so a requirements file is not needed.                                                                         |
| 22 | The programs can be run using Python.                            | Yes         | The uploaded files contain Python source code.                                                                                                           |
| 23 | The programs require external libraries.                         | No          | No external libraries are imported in the provided programs.                                                                                             |
| 24 | The repository contains a `LICENSE` file.                        | Not claimed | No licence claim is made in the README.                                                                                                                  |



The README claims were checked against the actual source code. Claims that could not be supported by the repository were not included as factual features.
