# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## DATE:
08.06.2026

## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm

1. Start the program.
2. Declare an integer variable for age.
3. Get the age from the user.
4. Check whether the age is greater than or equal to 21.
5. If true, display Eligible for marriage.
6. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int age;

    scanf("%d", &age);

    if(age >= 21)
    {
        printf("Eligible for marriage");
    }

    return 0;
}
```

## Output:

```text
23
Eligible for marriage
```

## Result:
Thus the program was executed and the output was verified successfully.
