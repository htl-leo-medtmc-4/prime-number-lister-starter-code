#  Prime Number Lister

## Topics
- Variables
- Selections
- Loops
- Functions

## Assignment
### Basic
Implement a Swift command line tool which lists the first $n$ prime numbers. Desired output
```
The first 9 prime numbers are:
# 1: 2
# 2: 3
# 3: 5
# 4: 7
# 5: 11
# 6: 13
# 7: 17
# 8: 19
# 9: 23
```
Keep the `run` function clean, i.e. it should only contain a head line and a call to a function named `listPrimeNumbers(.)`. Furthermore seperate the logic of checking a number for being prime into another function called `isPrime()`. Take care that the call should be possible without stating a label (`isPrime(5)` and not `isPrime(n: 5)`).

### Advanced
Parse the number of primes via a command line argument. The user interface should be as follows:

```
PrimeNumberLister --help
USAGE: prime-number-lister [<number-of-primes>]

ARGUMENTS:
  <number-of-primes>      Number of primes. (default: 10)

OPTIONS:
  -h, --help              Show help information.

primeNumberLister
The first 10 prime numbers are:
# 1: 2
# 2: 3
# 3: 5
# 4: 7
# 5: 11
# 6: 13
# 7: 17
# 8: 19
# 9: 23
# 10: 29

primeNumberLister 5
The first 5 prime numbers are:
# 1: 2
# 2: 3
# 3: 5
# 4: 7
# 5: 11
```


## Rubrics
First and most important: your program must be a runnable (must compile and link) Swift program. If this is the case, the grading will take place along the following table:

| Status of Project                                            | Score |
| ---| ---- |
| Program is basically complete but contains bugs              | 20 % |
| Program is complete and bug free (output is as required in the assignment)                   | 30 % |
| Program logic is separated in functions                      | 35 % |
| General appearance of code | 15 % |
