# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:

Write a java program to find the index of the last occurrence of a character in a string.
## AIM:
To write a java program to find the index of the last occurrence of a character in a string.

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
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        String input=sc.nextLine();
        char ch = sc.next().charAt(0);
        int index=input.lastIndexOf(ch);
        if(index != -1){
            System.out.println("Last occurrence of '"+ch+"' is at index: "+index);
        }

    }
}
```






## OUTPUT:



## RESULT:
Thus, the Java program to reverse a given string was executed successfully.

