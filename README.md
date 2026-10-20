# Python Practice — 50 Number Problems

Solutions to 50 classic number-logic practice problems (even/odd, primes,
Armstrong, Harshad, factorials, GCD/LCM, permutations & combinations, …),
written in a single Jupyter notebook: [`python_practice.ipynb`](python_practice.ipynb).

Each problem has a markdown cell with the statement, input and output format,
followed by a code cell with the solution.

## Contents

| # | Problem | # | Problem |
|---|---------|---|---------|
| 1 | Even or odd | 26 | Perfect / abundant / deficient |
| 2 | Positive, negative or zero | 27 | Strong number |
| 3 | Greatest of two | 28 | Harshad number |
| 4 | Greatest of three | 29 | Automorphic number |
| 5 | Leap year | 30 | Factorial |
| 6 | Sum of first N naturals | 31 | Power of a number |
| 7 | Count digits | 32 | Sum of an AP |
| 8 | Sum of digits | 33 | Sum of a GP |
| 9 | Reverse digits | 34 | Fibonacci series |
| 10 | Palindrome number | 35 | GCD of two numbers |
| 11 | Max and min digit | 36 | LCM of two numbers |
| 12 | Count a digit's occurrences | 37 | Count factors |
| 13 | Frequency of every digit | 38 | Sum of factors |
| 14 | Replace 0s with 1s | 39 | Co-prime check |
| 15 | Remove a given digit | 40 | GCD of an array |
| 16 | Product of digits | 41 | Neon number |
| 17 | Repeated digit sum | 42 | Spy number |
| 18 | Sum of squares of digits | 43 | Duck number |
| 19 | Prime check | 44 | Disarium number |
| 20 | Primes in a range | 45 | Happy number |
| 21 | Prime factors | 46 | Area of a circle |
| 22 | Sum of two primes | 47 | Roots of a quadratic |
| 23 | Armstrong number | 48 | Permutations (nPr) |
| 24 | Perfect number | 49 | Combinations (nCr) |
| 25 | Abundant number | 50 | Add and simplify fractions |

## Running it

The notebook needs only the Python standard library.

```bash
python -m venv .venv
source .venv/Scripts/activate    # Windows: .venv\Scripts\activate
pip install jupyter
jupyter lab python_practice.ipynb
```

Or open it in VS Code / PyCharm with the Jupyter extension and pick the
`Python 3` kernel. Most cells read from `input()`, so run them interactively.

## Notes

- The original question paper (`*.pdf`) is intentionally **not** tracked —
  see [`.gitignore`](.gitignore).
- Solutions favour readability over cleverness: plain loops and `str`
  handling, no third-party packages.
