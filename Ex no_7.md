# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1.Start

2.Declare integer variables n, i, and j

3.Read the value of n (number of rows) from the user

4.Set i = 1

5.Repeat the following steps while i <= n:
## Program:
```
#include <stdio.h>

int main()

{

int n, i, j;

printf("Enter the number of rows: ");

scanf("%d", &n);

for(i = 1; i <= n; i++) {

for(j = 1; j <= i; j++) {

printf("*");

}

printf("\n");

}

return 0;
}
```

## Output:
<img width="392" height="181" alt="image" src="https://github.com/user-attachments/assets/9311f477-523f-4cda-9284-29cc1ef2062d" />

## Result:
Thus the program was executed and the output was verified successfully.
