# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm 

1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number for multiplication and division.
6. End. 


## Program:
```c
#include<stdio.h>
void multiply(int a,int b); 
void div(int a,int b);
int main ()
{
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b);
div(a,b);
}
void multiply(int a,int b)
{
int product; 
product= a*b;
printf("Multiplication: %d",product);
}
void div(int a,int b)
{
int result; 
result=a/b;
printf("\nDivision: %d",result);
}
```

## Output:

![image](https://github.com/user-attachments/assets/a99a56cf-e167-4931-83a1-7b8ba29dfaf3)


## Result:
Thus the program was executed and the output was verified successfully.
