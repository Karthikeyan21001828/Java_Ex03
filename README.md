# EXP -3 Java program to find the number of day in a month
## AIM:
to write a java program to find the number of day in a month.
## PROCEDURE:
### STEP 1:
Import the required packages.
### STEP 2:
Get the month number from the user.
### STEP 3:
Assign number of days based on month number using switch statement.
### STEP 4:
Display number of days in the month.
### STEP 5:
Stop the execution.
## PROGRAM:
```java
import java.util.Scanner;
public class DaysInMonth
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Month number: ");
        int mon_no=sc.nextInt();
        int days=0;
        switch(mon_no)
        {
            case 1:
                days=31;
                break;
            case 2:
                days=28;
                break;
            case 3:
                days=31;
                break;
            case 4:
                days=30;
                break;
            case 5:
                days=31;
                break;
            case 6:
                days=30;
                break;
            case 7:
                days=31;
                break;
            case 8:
                days=31;
                break;
            case 9:
                days=30;
                break;
            case 10:
                days=31;
                break;
            case 11:
                days=30;
                break;
            case 12:
                days=31;
                break;
        }
        System.out.println("Number of days in the month is "+days);
    }
}

```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/Java_Ex03/assets/93427303/8da41015-3c38-4d5a-aa6d-08368080af0a)
## RESULT:
A java program to find the number of day in a month has been executed successfully.
