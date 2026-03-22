
# EX - 1A : PRINT ALL NUMBERS

## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## ALGORITHM:

1.Start the program.

2.Read an integer input N from the user.

3.Check if N is less than or equal to 0.

4.If yes, display the message: "Invalid input. N must be greater than 0."

5.If N is greater than 0, use a for loop to iterate from 1 to N.

6.Print each number separated by a space on the same line. 

## PROGRAM:
```
/*
Program to implement Reverse a String
Developed by:RESHMA R
Register Number:212224040274
*/

import java.util.*;
public class demo
{
    public static void main(String arg[])
    {
        int N,i;
        Scanner sc=new Scanner(System.in);
        N=sc.nextInt();
        if (N<=0)
        {
            System.out.println("Invalid input. N must be greater than 0.");
        }
        else
        {
            for(i=1;i<=N;i++)
            {
                System.out.print(i+" ");
            }
        }
        
    }
}

```

## OUTPUT:

<img width="572" height="188" alt="image" src="https://github.com/user-attachments/assets/feda1ddc-f530-41b5-9fef-4b59271fa6a5" />



## RESULT:
The program successfully print all the numbers from 1 to N. 
