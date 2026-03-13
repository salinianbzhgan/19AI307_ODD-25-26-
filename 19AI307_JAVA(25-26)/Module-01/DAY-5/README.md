# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a Java program to reverse a given string.

Example: Input: welcome

Output: Reversed string: emoclew
## AIM:
To write a Java program that reads a string from the user and reverses it by traversing the characters in reverse order.

## ALGORITHM :
1.Start the program.
2.Import the necessary package 'java.util'
3.Read n elements and store them in the array.
4.Initialize a variable maxOdd with the smallest possible integer value and set found = false.
5.Traverse each element in the array:
6.If the element is odd (arr[i] % 2 != 0)
7.If no odd number was found yet or the current element is greater than maxOdd, update maxOdd.
8.Set found = true.If true then print maxOddElse then print "No odd number found"



## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: SALINI A
RegisterNumber:  212223220091
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        String str = scanner.next();
        String newstr = "";

        for (int i = str.length() - 1; i >= 0; i--) {
            newstr += str.charAt(i);
        }

        System.out.println("Reversed string: " + newstr);

        scanner.close();
    }
}
```






## OUTPUT:



## RESULT:
Thus, the Java program to reverse a given string was executed successfully.
