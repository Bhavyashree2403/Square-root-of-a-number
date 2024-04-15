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
#Square root of a number
#Developed by: BHAVYASHREE . R
#Register number: 212223110006
def newton_square_root(b):
    if b<0:
        print("The Square root is not defined for negative number")
    x=b/2.0
    while True:
        new_x=0.5*(x+b/x)
        if new_x==x:
            break
        x=new_x
    return x
b=int(input())
result = newton_square_root(b)
print(f"Square root of the number: {result}")
```

## Output:
![Screenshot 2024-04-15 133933](https://github.com/Bhavyashree2403/Square-root-of-a-number/assets/149219738/04315203-d11f-4607-9c3d-0cde0fdf8bdd)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
