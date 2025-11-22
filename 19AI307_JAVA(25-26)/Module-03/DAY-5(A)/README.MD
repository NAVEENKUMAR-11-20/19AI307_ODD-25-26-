# Ex.No:3(E) INNER CLASS

## QUESTION:

Write a Java program to convert a string to an integer using a wrapper class and perform addition.

## AIM:


## ALGORITHM :
1.Algorithm (Short):

2.Read two strings

3.Convert both strings to integers

4.Add the two integers

5.Print the sum

6.End



## PROGRAM:
 ```
/*
Program to implement a InnerClass using Java
Developed by: NAVEEN KUMAR P
RegisterNumber:  212224240102
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class StringToIntegerAddition
{
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
        String str1 = scanner.nextLine();
        String str2 = scanner.nextLine();
        int n = Integer.parseInt(str1);
        int m = Integer.parseInt(str2);
        int sum = n + m;
        System.out.println("Sum = " + sum);
        scanner.close();
    }
}


```



## OUTPUT:

<img width="666" height="488" alt="image" src="https://github.com/user-attachments/assets/5ede3651-6f94-42b0-a855-eed9632bde51" />


## RESULT:

The program converts two input strings into integers, adds them, and prints the sum.
