# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Start the program and declare a variable for the number and sum of odd digits.

2.Read the number from the user.

3.Use a do-while loop to extract each digit of the number.

4.If the digit is odd, add it to the sum.

5.Display the sum of odd digits.

## Program:
```
#include <stdio.h>

int main()
{
    int num, sum = 0, digit;

    printf("Enter a number: ");
    scanf("%d", &num);

    do
    {
        digit = num % 10;
        if(digit % 2 != 0)
        {
            sum += digit;
        }
        num /= 10;
    } while(num != 0);

    printf("Sum of odd digits = %d\n", sum);

    return 0;
}

```

## Output:
<img width="388" height="231" alt="image" src="https://github.com/user-attachments/assets/e09f8266-71ef-4335-ac5f-7731560fb9b4" />

## Result:
Thus the program was executed and the output was verified successfully.
