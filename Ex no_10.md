# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1.Start the program and declare a function factorial(int) with return type.

2.Read a number from the user.

3.Call the factorial function with the number as an argument.

4.Compute factorial in the function using a loop and return result.

5.Display the result in main.

Program:
## Program:
```
#include <stdio.h>

// Function to calculate factorial
int factorial(int n)
{
    int i, fact = 1;
    for(i = 1; i <= n; i++)
    {
        fact *= i;
    }
    return fact;
}

int main() {
    int num, result;
    
    printf("Enter a number: ");
    scanf("%d", &num);
    
    result = factorial(num);
    printf("Factorial of %d = %d\n", num, result);
    
    return 0;
}

```

## Output:
<img width="376" height="209" alt="image" src="https://github.com/user-attachments/assets/63fb9f01-604a-4fd5-b041-d9c8b9657bff" />

## Result:
Thus the program was executed and the output was verified successfully.
