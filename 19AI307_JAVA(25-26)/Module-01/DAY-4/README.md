# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to find the maximum odd number in an array.

## AIM:
To write a program to find the maximum odd number in an array.

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
Program to implement a Array concept using Java
Developed by: SALINI A 
RegisterNumber: 212223220091 
*/
```

## SOURCE CODE:
```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int[] arr=new int[n];
        
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        int maxOdd=Integer.MIN_VALUE;
        boolean found=false;
        
        for(int i=0;i<n;i++){
            if(arr[i] % 2 != 0){
                if(!found || arr[i] >maxOdd){
                    maxOdd=arr[i];
                }
                found=true;
            }
        }
        if(found){
            System.out.println(maxOdd);
        }
        else{
            System.out.println("No odd number found");
        }
        
    }
}
```






## OUTPUT:






## RESULT:
Thus, the program to find the maximum odd number in an array is executed successfully.

