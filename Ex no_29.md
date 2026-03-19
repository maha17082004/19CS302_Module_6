# EX 29 C program to create two float variables using calloc() and find minimum among them.
## DATE:
## AIM:
To write a C program to create two float variables using calloc() and find minimum among them.

## Algorithm
1. Start.
2. Initialize two variables value of calloc().
3. Prompt the user to enter values.
4. Read the values using scanf.
5. Find minimum and print result
6. End   
  

## Program:
```
/*
C program to create two float variables using calloc() and find minimum among them.
Developed by: MAHALAKSHMI A
RegisterNumber:212222060139

#include <stdio.h>
#include <stdlib.h>
int main() {
 int *num1, *num2, minimum;
 num1 = (int *)calloc(1, sizeof(int));
 num2 = (int *)calloc(1, sizeof(int));
 num1= 5.8 , num2 = 6.5;
 minimum = (*num1 < *num2) ? *num1 : *num2;
 printf("%d\n", minimum);
 free(num1);
 free(num2);
*/
```

## Output:
<img width="627" height="295" alt="image" src="https://github.com/user-attachments/assets/13227d87-e33b-48bb-9a57-06adeb22725b" />


## Result:
Thus the program was executed and the output was verified successfully.
