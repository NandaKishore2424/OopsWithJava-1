# EX.NO 1(D): Student Details with Static Age
## DATE:
## Name: Nanda Kishore R
## Reg.no: 212222060157

## AIM:
To write a Java program to display the name and age of students, where the age is the same for all students and is stored in a static variable.

## Algorithm:

1. Create a class named Main.

2. Add a static integer variable age and initialize it to 18.

3. Add a non-static string variable name to store the student’s name.

4. In the main() method:

    > Create two objects of the Main class.

    > Use the Scanner class to read names for the two students.

    > Assign the names to each object’s name variable.

    > Print the name and age for each student using the static age variable.

## Program:

```
import java.util.*;
public class Main
{
    static String dept="AIDS";
    String name;
    static int age=18;
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	Main obj1=new Main();
	Main obj2=new Main();
	obj1.name=sc.next();
	obj2.name=sc.next();
	System.out.println("Student name: "+obj1.name+"Age: 18");
	System.out.println("Student name: "+obj2.name+"Age: 18");
	}
}

```

## Output:
![image](https://github.com/user-attachments/assets/51b5fac1-c40f-4782-a5ae-59907421ced8)


## Result:
Thus, the Java program to input and display student details (name and static age) for multiple students is implemented successfully.
