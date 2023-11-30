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
/*
Program to find the square root for the given number(newton's method) using function.
Developed by: A.Bhagathkrishna
RegisterNumber:23002963
def square_root_newton(number):
    x=number/2.0
    iterations=100
    for i in range(iterations):
        x=0.5*(x+number/x)
    return x
a=int(input())
result=square_root_newton(a)
print("Square root of the number:",result)
  
*/
```

## Output:
![output]![square](https://github.com/Bhagath118/Square-root-of-a-number/assets/147473779/916d94c7-8a5b-45f2-b8aa-d3f4414ae88f)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
