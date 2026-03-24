# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1.Start the program and declare two functions for multiplication and division.

2.Define functions that take no arguments and return no value.

3.Read two numbers from the user.

4.Call the functions to perform multiplication and division.

5.Display the results.
## Program:
```
#include <stdio.h>

void multiply()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    printf("Multiplication = %d\n", a * b);
}

void divide()
{
    int a, b;
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);
    if(b != 0)
    {
        printf("Division = %.2f\n", (float)a / b);
    }
    else
    {
        printf("Division by zero is not allowed.\n");
    }
}

int main()
{
    multiply();
    divide();
    return 0;
}

```

## Output
<img width="367" height="261" alt="image" src="https://github.com/user-attachments/assets/a183c04d-9ff2-404f-9b37-3b635b15ef80" />

## Result:
Thus the program was executed and the output was verified successfully.
