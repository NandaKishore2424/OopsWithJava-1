# EX.NO 1(C): Determine Integer Sign Status
## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that reads an integer m from the user and displays the value of n as:

> 1 if m is greater than 0

> 0 if m is equal to 0

> -1 if m is less than 0



## Algorithm:

1. Import the Scanner class.

2. Create the main() method inside a class named Main.

3. Read the integer m from the user.

4. Use if conditions to check whether m is:

   > Greater than 0: set n to 1.

   > Equal to 0: set n to 0.

   > Less than 0: set n to -1.

5. Display the values of m and n.

## Program:

```
import java.util.*;
public class main{
    public static void main(String args[]){
        Scanner in =new Scanner(System.in);
        int a=in.nextInt();
        int f;
        if(a==0)
        {
            f=0;
            System.out.println("The value of m = "+a+"\nThe value of n = "+f);
        }
        if(a>0){
            f=1;
        System.out.println("The value of m = "+a+"\nThe value of n = "+f);
        }
        if(a<0)
        {
            f=-1;
            System.out.println("The value of m = "+a+"\nThe value of n = "+f);
        }
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/a35299a7-953c-4ea3-926b-7a74a409abed)


## Result:
Thus, the Java program to read an integer from the user and determine the sign status of that integer (positive, zero, or negative) is implemented successfully.
