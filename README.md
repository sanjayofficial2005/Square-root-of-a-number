# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```python
#Program Developed by: SANJAY M
#Register No:212223230187


def newton_method(number,iterations=100):
    for i in range(iterations):
        number=0.5*(number+inp/number)
    return number
inp=int(input())
print("Square root of the number:",newton_method(inp))
```

## Output:
![Screenshot 2024-03-24 102458](https://github.com/sanjayofficial2005/Square-root-of-a-number/assets/148048602/012b0977-3763-4513-aa89-2855c5f44360)

![Screenshot 2024-03-24 102520](https://github.com/sanjayofficial2005/Square-root-of-a-number/assets/148048602/160cc498-27b0-4542-b57b-965d1e795191)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
