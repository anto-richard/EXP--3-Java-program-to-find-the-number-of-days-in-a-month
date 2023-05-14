# <p align="center">EXP-3-Java-program-to-find-the-number-of-days-in-a-month...</p>

## AIM:

To write a java program to find the number of days in a month.

## ALGORITHM:

### Step 1:

Import the necessary packages.

### Step 2:

Get the value from the user.

### Step 3:

Find the number of days in a month using switch case.

### Step 4:

Print the result.

### Step 5:

End the program.

## PROGRAM:

```java

Name : Anto Richard. S
Register Number : 212221240005
Java program to find the number of days in a month.

```

```java

import java.util.*;
public class MonthDays {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter a month from (1-12): ");
        int month = s.nextInt();

        switch (month) {
            case 1:
                System.out.println("January has 31 days");
                break;
            case 2:
                System.out.print("Enter a year: ");
                int year = s.nextInt();
                int days;
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                    days = 29;
                } else {
                    days = 28;
                }
                System.out.println("February has " + days + " days");
                break;
            case 3:
                System.out.println("March has 31 days");
                break;
            case 4:
                System.out.println("April has 30 days");
                break;
            case 5:
                System.out.println("May has 31 days");
                break;
            case 6:
                System.out.println("June has 30 days");
                break;
            case 7:
                System.out.println("July has 31 days");
                break;
            case 8:
                System.out.println("August has 31 days");
                break;
            case 9:
                System.out.println("September has 30 days");
                break;
            case 10:
                System.out.println("October has 31 days");
                break;
            case 11:
                System.out.println("November has 30 days");
                break;
            case 12:
                System.out.println("December has 31 days");
                break;
            default:
                System.out.println("Invalid input, a year has only 12 months!!!");
                break;
        }
    }
}


```

## OUTPUT:

![o3](https://github.com/anto-richard/EXP-3-Java-program-to-find-the-number-of-days-in-a-month/assets/93427534/bea1a301-c6b5-4fab-862c-540546b33fb8)

## RESULT:

Thus the java program to find the number of days in a month is written and implemented successfully.

