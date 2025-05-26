# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## AlgorithmStart the program.

Initialize a variable to store the sum of odd digits (e.g., sum = 0).

Input the number from the user (e.g., num).

Set a loop to iterate through each digit of the number:

Use the do-while loop to extract the last digit of the number.

Check if the extracted digit is odd:

If it is odd (i.e., digit % 2 != 0), add it to the sum.

Remove the last digit from the number (i.e., num = num / 10).

Repeat the loop until the number becomes zero.

Display the sum of the odd digits.

End the program.
 
## Program:
```c
#include <stdio.h>
 int main()
 {
   int num, digit, sum = 0;
  scanf("%d", &num);
  if (num < 0) {
   num = -num;
  }
 do
 {
   digit = num % 10;
        if (digit % 2 != 0) {
          sum += digit;
 }
  num = num / 10;
     }
while (num != 0);
  printf("Sum of odd digits is: %d\n", sum);
   return 0;
 }
```

## Output:

![image](https://github.com/user-attachments/assets/d571354a-a2b3-4031-bd12-40d0120b43d1)


## Result:
Thus the program was executed and the output was verified successfully.
