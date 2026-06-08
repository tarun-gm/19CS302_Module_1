# EX 2 C program to check whether the attendance is PRESENT using simple if statement.

## DATE:
08.06.2026

## AIM:
To write a program to check whether the attendance is PRESENT using simple if statement.

## Algorithm

1. Start the program.
2. Declare an integer variable for attendance.
3. Get the attendance value from the user.
4. Check whether the attendance value is 1 using if statement.
5. If true, display PRESENT.
6. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int attendance;

    scanf("%d", &attendance);

    if(attendance == 1)
    {
        printf("PRESENT");
    }

    return 0;
}
```

## Output:

```text
1
PRESENT
```

## Result:
Thus the program was executed and the output was verified successfully.
