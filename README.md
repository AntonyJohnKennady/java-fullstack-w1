## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
    System.out.println("Enter a and b :");
    Scanner cal=new Scanner(System.in);
    int a=cal.nextInt();
    int b=cal.nextInt();
    int sum=a+b;
    System.out.println("Sum of a and b is: "+sum);
    int sub=a-b;
    System.out.println("Subtract of a and b is: "+sub);
    int mul=a*b;
    System.out.println("Multiply of a and b is: "+mul);
    int divide= a/b;
    System.out.println("Division  of a and b is: "+divide);
    int mod= a%b;
    System.out.println("Modulus of  a and b is: "+mod);


    }
}
```
### Output
![gib](./1%20st%20op.png)

## 2.Write a Java program to compare two numbers
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        Scanner com=new Scanner (System.in);
        System.out.println("Enter A and B: ");
        int A=com.nextInt();
        int B=com.nextInt();
        if(A>B){
            System.out.println("A is Greatest");
        }
        else if(B>A){
            System.out.println("B is Greatest");
        }
        else{
            System.out.println("A and B are Equal");
        }


    }
}
```
### Output
![anto](./2nd%20op.png)

## 3.Write a Java program to convert a string to an integer
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        Scanner con=new Scanner (System.in);
        System.out.println("Enter the value:");
        int a= con.nextInt();
        String b= String.parseInt(a);
        System.out.println("String to Integer is: "+b);


    }
}
```
### Output
![john](./3rd%20op.png)
## 4.Java Program to find area of rhombus
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        Scanner cal=new Scanner (System.in);
        System.out.println("Enter the d1 and d2 value:");
        int d1= cal.nextInt();
        int d2= cal.nextInt();
        float area=(d1*d2)/2;
        System.out.println("Area of Rhombus is: "+area);


    }
}
```
### Output
![ken](./4th%20op.png)
## 5.Write a Java program to find the number of days in a month
## Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {

        Scanner input = new Scanner(System.in);

        int Days=0;
        String Name = " ";

        System.out.print("Enter the month number: ");
        int month = input.nextInt();

        System.out.print("Enter the year: ");
        int year = input.nextInt();

        switch (month) {
            case 1:
                Name = "January";
                Days = 31;
                break;
            case 2:
                Name = "February";
                if ((year % 400 == 0)||((year % 4 == 0)&&(year % 100 != 0))) {
                    Days= 29;
                } else {
                    Days = 28;
                }
                break;
            case 3:
                Name = "March";
                Days = 31;
                break;
            case 4:
                Name = "April";
                Days = 30;
                break;
            case 5:
                Name = "May";
                Days = 31;
                break;
            case 6:
                Name = "June";
                Days = 30;
                break;
            case 7:
                Name = "July";
                Days = 31;
                break;
            case 8:
                Name = "August";
                Days = 31;
                break;
            case 9:
                Name = "September";
                Days = 30;
                break;
            case 10:
                Name = "October";
                Days = 31;
                break;
            case 11:
                Name = "November";
                Days = 30;
                break;
            case 12:
                Name = "December";
                Days = 31;
        }
        System.out.println(Name + " " + year + " has " + Days + " days");
    }
}
```
### Output
![nal](./5th%20op.png)

## 6.Write a Java program to print the even numbers from 1 to 20
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
            Scanner input = new Scanner(System.in);
            int a = input.nextInt();
            for (int i=1; i<=a; i++)
            {
                if (i%2==0)
                {
                    System.out.print(i+" ");
                }
            }
        }
    }
```
### Output
![ram](./6th%20op.png)

## 7.Write a Java program to create a simple calculator
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        char operator;
        double num1, num2, result;
        Scanner input = new Scanner(System.in);
        System.out.println("Choose an operator: +, -, *, or /");
        operator = input.next().charAt(0);
        System.out.println("Enter first number");
        num1 = input.nextDouble();
        System.out.println("Enter second number");
        num2 = input.nextDouble();

        switch (operator) {

            case '+':
                result = num1 + num2;
                System.out.println(num1 + " + " + num2 + " = " + result);
                break;

            case '-':
                result = num1 - num2;
                System.out.println(num1 + " - " + num2 + " = " + result);
                break;

            case '*':
                result = num1 * num2;
                System.out.println(num1 + " * " + num2 + " = " + result);
                break;

            case '/':
                result = num1 / num2;
                System.out.println(num1 + " / " + num2 + " = " + result);
                break;

            default:
                System.out.println("Invalid operator!");
                break;
        }
    }
}
```
### Output
![ya](./7th%20op.png)

## 8. Write a Java program to print multiplication table of given number
### Program
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s = new Scanner(System.in);
        System.out.print("Enter number: ");
        int n=s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(n+" * "+i+" = "+n*i);
        }
    }
}
```
### Output
![ni](./8th%20op.png)