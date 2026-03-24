
# EX 1A Print All Numbers 
## DATE : 26/11/2025
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm
1. Start

2. Input an integer N from the user.

3. Initialize a counter variable i = 1.

4. Repeat while i ≤ N:

5. Print i followed by a space.

6. Increment i by 1.

#### Developed By: JAYARAJ B
#### Register Number: 212223043002

## Program:
```java
import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        
        int n = sc.nextInt();
        
        for(int i=1;i<=n;i++)
        {
            System.out.print(i+" ");
        }
    }
}


```

## Output:
<img width="768" height="297" alt="512189884-0316db62-2960-44b3-bee8-8936fe6a3dbe" src="https://github.com/user-attachments/assets/46d8e4e3-1d11-4215-a6b4-8aec7f538d2d" />

## Result:

The program successfully print all the numbers from 1 to N.
