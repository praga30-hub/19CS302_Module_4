# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.

## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Start.
2.Input: Read an integer num from the user.

3.Define Shift Value: Set a variable shiftBits to the number of positions you want to shift (in this case, 2 bits).

4.Perform Left Shift:

Compute leftShift = num << shiftBits (Shift the bits of num to the left by shiftBits positions).

5.Perform Right Shift:

Compute rightShift = num >> shiftBits (Shift the bits of num to the right by shiftBits positions).

6.Output: Display the original number, the result of the left shift, and the result of the right shift.

7.End.
   

## Program:
```
#include <stdio.h>

int main() {
    int num, leftShift, rightShift;
    int shiftBits = 2; // You can change the number of bits to shift

    // Input an integer from the user
    printf("Enter an integer: ");
    scanf("%d", &num);

    // Perform left shift (shift by 'shiftBits' positions)
    leftShift = num << shiftBits;

    // Perform right shift (shift by 'shiftBits' positions)
    rightShift = num >> shiftBits;

    // Display the results
    printf("Original number: %d\n", num);
    printf("After left shift by %d: %d\n", shiftBits, leftShift);
    printf("After right shift by %d: %d\n", shiftBits, rightShift);

    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/fbd8cf3e-301b-4fb8-a52c-f3624d26e70f)



## Result:
Thus the program was executed and the output was verified successfully.
