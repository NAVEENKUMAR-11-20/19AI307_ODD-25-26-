# Ex.No:3(F) WRAPPER CLASS

## QUESTION:

Write a Java program to find the square root of a number using Double wrapper class.

## AIM:

To write a Java program that uses the Double wrapper class to convert input into a numeric value and compute the square root of the given number.


## ALGORITHM :
1. Start

2. Read a string input

3. Convert the string to a `Double` using `Double.valueOf()`

4. Compute the square root using `Math.sqrt()`

5. Print the result

6. End


## PROGRAM:
 ```
/*
Program to implement a Wrapper Class using Java
Developed by: NAVEEN KUMAR P
RegisterNumber:  212224240102
*/
```

## SOURCE CODE:

```java
import java.util.Scanner;
public class SquareRoot 
{
    public static void main(String[] args)
    {
        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();
        Double num = Double.valueOf(input);
        Double sqrt = Math.sqrt(num);
        System.out.println("Square root of " + num + " is: " + sqrt);
        scanner.close();
    }
}
```


## OUTPUT:

<img width="875" height="452" alt="image" src="https://github.com/user-attachments/assets/3a8478b7-284b-4015-86a3-774af1587223" />

## RESULT:

The program converts a string to a double, calculates its square root, and displays the result.**




