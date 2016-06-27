# Calculator

import java.util.Scanner;


public class Calculator {


    public static void main(String[] args) {

        Scanner kb = new Scanner(System.in);

        System.out.println("Calculator");

        System.out.println("\nHere are your options:");
        System.out.println("\n1. Addition");
        System.out.println("2. Subtraction");
        System.out.println("3. Division");
        System.out.println("4. Multiplication");

        System.out.print("\nWhat would you like to do?: ");
        int choice = kb.nextInt();
        System.out.println();


        if (choice == 1){
            addition();
        }
        else if (choice == 2){
            subtraction();
        }
        else if (choice == 3){
            division();
        }
        else if (choice == 4){
            multiplication();
        }

        System.out.println();
        kb.close();
    }

    public static void addition(){

        int nOne, nTwo;
        Scanner kb = new Scanner(System.in);

        System.out.println("Addition");

        System.out.print("\nFirst Number: ");
        nOne = kb.nextInt();

        System.out.print("\nSecond Number: ");
        nTwo = kb.nextInt();

        kb.close();
        System.out.println("\nSum: " + nOne + " + " + nTwo + " = " + (nOne + nTwo));
    }

    public static void subtraction(){
        int nOne, nTwo;
        Scanner kb = new Scanner(System.in);

        System.out.println("Subtraction");

        System.out.print("\nFirst Number: ");
        nOne = kb.nextInt();

        System.out.print("\nSecond Number: ");
        nTwo = kb.nextInt();

        kb.close();
        System.out.println("\nSum: " + nOne + " - " + nTwo + " = " + (nOne - nTwo));
    }

    public static void division(){
        int nOne, nTwo;
        Scanner kb = new Scanner(System.in);

        System.out.println("Division");

        System.out.print("\nFirst Number: ");
        nOne = kb.nextInt();

        System.out.print("\nSecond Number: ");
        nTwo = kb.nextInt();

        kb.close();
        System.out.println("\nSum: " + nOne + " / " + nTwo + " = " + (nOne / nTwo));
    }

    public static void multiplication(){
        int nOne, nTwo;
        Scanner kb = new Scanner(System.in);

        System.out.println("Multiplication");

        System.out.print("\nFirst Number: ");
        nOne = kb.nextInt();

        System.out.print("\nSecond Number: ");
        nTwo = kb.nextInt();

        kb.close();
        System.out.println("\nSum: " + nOne + " x " + nTwo + " = " + (nOne * nTwo));
    }
}

Output: 1
Calculator

Here are your options:

1. Addition
2. Subtraction
3. Division
4. Multiplication

What would you like to do?: 1

Addition

First Number: 2

Second Number: 3

Sum: 2 + 3 = 5

Output 2:
Calculator

Here are your options:

1. Addition
2. Subtraction
3. Division
4. Multiplication

What would you like to do?: 2

Subtraction

First Number: 99

Second Number: 66

Sum: 99 - 66 = 33

Output 3:
Calculator

Here are your options:

1. Addition
2. Subtraction
3. Division
4. Multiplication

What would you like to do?: 3

Division

First Number: 100

Second Number: 4

Sum: 100 / 4 = 25

Output 4:
Calculator

Here are your options:

1. Addition
2. Subtraction
3. Division
4. Multiplication

What would you like to do?: 4

Multiplication

First Number: 25

Second Number: 25

Sum: 25 x 25 = 625



