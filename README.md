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
```

Program to find the square root for the given number(newton's method) using function.
Developed by:S.Vengada Krishnan
RegisterNumber: 212223110061
def n(num,iter=100):
    for i in range(iter):
        num=0.5*(num+inp/num)
    return num
inp=int(input())
print("Square root of the number:",n(inp))

```

## Output:

![sq root](https://github.com/SVENGADAKRISHNAN/Square-root-of-a-number/assets/147473084/d39a63b6-8372-47bf-9c52-9ee57dba4167)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
