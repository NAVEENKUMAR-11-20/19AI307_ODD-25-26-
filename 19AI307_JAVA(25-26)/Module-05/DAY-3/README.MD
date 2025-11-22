# Ex.No:5(C)  FILE HANDLING USING JAVA
## QUESTION:

Read a file and print only the lines containing the word "Java".

## AIM:

To write a Java program that reads a file and displays only the lines that contain the word **"Java"**.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	





## PROGRAM:
 ```
/*
Program to implement a File Handling using Java
Developed by: NAVEEN KUMAR P
RegisterNumber:  212224240102
*/
```

## SOURCE CODE:

```java
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class JavaLineFilter {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        List<String> linesWithJava = new ArrayList<>();
        while (true) {
            String line = scanner.nextLine();
            if (line.equalsIgnoreCase("exit")) {
                break;
            }
            if (line.contains("Java")) 
            { 
                linesWithJava.add(line);
            }
        }
        
        System.out.println("Lines containing the word 'Java':");
        for (String javaLine : linesWithJava) {
            System.out.println(javaLine);
        }
        
        scanner.close();
    }
}

```


## OUTPUT:

<img width="1260" height="484" alt="image" src="https://github.com/user-attachments/assets/bd3d0201-57c4-4650-97af-eb73eb7b1948" />


## RESULT:

The program transfers user input from one thread to another using piped streams and displays the received message.
