# student-assignment3
```# Factorial Program (Python)

This program calculates the factorial of a number using recursion.

## Code

```python
n = int(input('Enter the number: '))

def factorial(n):
    if n < 2:
        return 1
    else:
        return n * factorial(n - 1)

print('Factorial is', factorial(n))
```
```
