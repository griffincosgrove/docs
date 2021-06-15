---
Title: "Python Random Module: `randint()`"
Subjects:
  - "Language Fluency"
  - "Code Foundations"
Tags:
  - "Function"
  - "Methods"
  - "Strings"
Catalog Content:
  - "https://www.codecademy.com/learn/learn-python-3"
  - "https://www.codecademy.com/learn/paths/analyze-data-with-python"
---

## Definition
***
An alias for `randrange(start, end(+1))`, which takes as input two `int` values, and returns a pseudo-random integer within the defined range of `int` values.

## Syntax
***
random.randint(start, end)

## Example 1
***
Use `randint()` to return a random number between `0` and `50`:
```codebyte/python
import random

print(random.randint(0, 50))
```

## Example 2
***
Use `randint()` to return a random number between `-25` and `25`:
```codebyte/python
import random

print(random.randint(-25, 25))
```