# EX.NO 1: Program to Display Employee In-Date in Day/Month/Year Format
## DATE: 
## AIM:

To write a Java program that takes input from the user for day, month, and year of an employee's in-date and display it in the format day/month/year using a Clock class and a Test class.

## Algorithm:

1. Define a class Clock with three integer data members: day, mon, year.

2. In the Clock class, define a method printDetails() to print the date in the format day/month/year.

3. In the Test class, create the main() method.

4. Inside the main() method,

  > Create an object of the Clock class.

  > Use Scanner to take input from the user for day, mon, and year.

  > Assign these values to the respective fields of the Clock object.

  > Call the printDetails() method of the Clock object to display the date.

## Program:

```
import java.util.Scanner;

class Clock {
    int day, mon, year;

    void printDetails() {
        System.out.println(day + "/" + mon + "/" + year);
    }
}

public class Test {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        // Create object of Clock
        Clock employeeDate = new Clock();

        // Get input from user
        System.out.println("Enter day: ");
        employeeDate.day = sc.nextInt();

        System.out.println("Enter month: ");
        employeeDate.mon = sc.nextInt();

        System.out.println("Enter year: ");
        employeeDate.year = sc.nextInt();

        // Display the date
        employeeDate.printDetails();

        sc.close();
    }
}

```

## Output:
![output](https://github.com/user-attachments/assets/fd9b6ec7-6ec9-4211-a959-4053f8ec30f2)



## Result:
Thus, the Java program to input and display the in-date of an employee in the format day/month/year is implemented successfully.




