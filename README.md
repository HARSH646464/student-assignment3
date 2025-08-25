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
```# Math Module Example in Python

This program demonstrates the use of the **math** module in Python.  
It performs the following operations on a user-input number:

- Calculates the *square root*
- Calculates the *sine*
- Calculates the *logarithm (natural log)*

## Code

```python
import math

def module():
    number = int(input('Enter the number: '))
    
    square_root = math.sqrt(number)
    print('Square root:', square_root)
    
    sin = math.sin(number)
    print('Sine:', sin)
    
    logarithim = math.log(number)
    print('Logarithim:', logarithim)

module()
```
