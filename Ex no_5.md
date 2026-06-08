# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## DATE:
08.06.2026

## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm

1. Start the program.
2. Declare variables for seven subject marks, total, average, and percentage.
3. Get the marks from the user.
4. Calculate the total marks.
5. Calculate the average marks.
6. Calculate the percentage.
7. Display the total, average, and percentage.
8. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    int s1, s2, s3, s4, s5, s6, s7, total;
    float average, percentage;

    scanf("%d %d %d %d %d %d %d",
          &s1, &s2, &s3, &s4, &s5, &s6, &s7);

    total = s1 + s2 + s3 + s4 + s5 + s6 + s7;

    average = total / 7.0;

    percentage = (total / 700.0) * 100;

    printf("Total = %d\n", total);
    printf("Average = %.2f\n", average);
    printf("Percentage = %.2f", percentage);

    return 0;
}
```

## Output:

```text
80 75 90 85 70 88 92

Total = 580
Average = 82.86
Percentage = 82.86
```

## Result:
Thus the program was executed and the output was verified successfully.
