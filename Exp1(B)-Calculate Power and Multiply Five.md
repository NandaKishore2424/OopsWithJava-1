# EX.NO 1(B): Calculate Power and Multiply Five
## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program that takes two integers as input from the user, calculates the first number raised to the power of the second number, and then multiplies the result by 5.

## Algorithm:

1. Import the Scanner and Math classes.

2. Create the class Demo and the main() method.

3. Use Scanner to get two integers (num1 and num2) from the user.

4. Calculate the power of num1 raised to num2 using Math.pow().

5. Multiply the result by 5.

6. Print the final result.

## Program:

```
import java.util.*;
import java.lang.Math;
public class Demo{
    public static void main(String[] args){
        Scanner in=new Scanner(System.in);
        int num1=in.nextInt();
        int num2=in.nextInt();
        System.out.println(Math.pow(num1,num2)*5);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/fa531806-8994-4aa7-bff7-1c21a2f33bbc)

## Result:
Thus, the Java program to calculate the power of one number raised to another and then multiply the result by 5 is implemented successfully.
