# EX-02-3c   FACTORIAL OF A NUMBER

## AIM:
To write a C program for finding the factorial of a given number .

## ALGORITHM:

1: Start the program.
2:Declare the variable fact(),i,n.
3: Initialize fact to 1.
4: Read the input value for n using scanf().
5: Set up a for loop that iterates from i=1 to i<=n.
6: Inside the loop, update fact by multiplying it with i.
7: After the loop completes, print the factorial value using printf().
8: Stop the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,n,fact=1;
    scanf("%d",&n);
    for(a=1;a<=n;a++)
    {
       fact=fact*a;
    }
    printf("Factorial value is: %d",fact);
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-02-3c/assets/121418522/2d9099f6-24bd-4aaf-9954-7630ec5169a6)

## RESULT:
  Thus, the program is successfully verified.
