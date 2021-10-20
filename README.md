# ECE444-F2021-Lab6
This repo is based on the following tutorial:

https://github.com/mjhea0/flaskr-tdd

## Test-Driven Development (TDD)

### Pros

Since the goal of TDD is to make all the tests pass, this design methodology helps to guide the development of code. It also helps to remove unnecessary features from the code, since these won't be tested (i.e. implementing these features won't improve the percentage of passing tests). Additionally, the written tests can be used as a backbone for regression testing, which is useful when code is refactored, a large feature is integrated, code is migrated to a different service, etc.

### Cons
Writing the tests beforehand can consume a considerable amount of time, especially when adopting an Agile design methodology and the requirements of the design may be in flux. Additionally, in order to apply TDD, the expected outputs of a design must be known, which isn't feasible in certain cases (e.g. machine learning applications).
