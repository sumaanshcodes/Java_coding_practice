public class AssignmentOnMethod {

    // Q1: Student Info
    public void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    // Q2: Add Two Numbers
    public int addNumbers(int a, int b) {
        return a + b;
    }

    // Q3: Greeting Message
    public String sayHello(String name) {
        return "Hello, " + name + "! Welcome to Java programming.";
    }

    // Q4: Area of Circle
    public double calculateArea(double radius) {
        double pi = 3.14;
        return pi * radius * radius;
    }

    // Q5: Simple Interest
    public double calculateInterest(double P, double T, double R) {
        return (P * T * R) / 100;
    }

    // Q6: Armstrong Number
    public boolean isArmstrong(int num) {
        int original = num;
        int sum = 0;
        while (num > 0) {
            int digit = num % 10;
            sum += digit * digit * digit;
            num /= 10;
        }
        return sum == original;
    }

    // Q7: Palindrome Number
    public boolean isPalindrome(int num) {
        int original = num;
        int reversed = 0;
        while (num > 0) {
            int digit = num % 10;
            reversed = reversed * 10 + digit;
            num /= 10;
        }
        return reversed == original;
    }

    public static void main(String[] args) {
        AssignmentOnMethod obj = new AssignmentOnMethod();

        System.out.println("Q1 Output:");
        obj.displayInfo();

        System.out.println("\nQ2 Output:");
        System.out.println("Sum: " + obj.addNumbers(15, 25));

        System.out.println("\nQ3 Output:");
        System.out.println(obj.sayHello("John"));

        System.out.println("\nQ4 Output:");
        System.out.println("Area of Circle: " + obj.calculateArea(7));

        System.out.println("\nQ5 Output:");
        System.out.println("Simple Interest: " + obj.calculateInterest(1000, 2, 5));

        System.out.println("\nQ6 Output:");
        System.out.println("153 is Armstrong? " + obj.isArmstrong(153));

        System.out.println("\nQ7 Output:");
        System.out.println("121 is Palindrome? " + obj.isPalindrome(121));
    }
}

//
//Q. -  Write a java program to print all alphabets from a to z - using loop.
//
//
//public class all_alphabets {
//    public static void main(String[] args) {
//        for (char c = 'a'; c <= 'z'; c++) {
//            System.out.print(c + " ");
//        }
//        System.out.println();
//        for (char c = 'A'; c <= 'Z'; c++) {
//            System.out.print(c + " ");
//        }
//
//
//    }
//}


//Q.- WAP to find is it a vowel or consonent?

import java.util.Scanner;

public class checkvowel {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String str = sc.next();
        if (str.equals("A") || str.equals("E") || str.equals("I") || str.equals("O") || str.equals("U")||str.equals("a") || str.equals("e") || str.equals("i") || str.equals("o") || str.equals("u")) {
            System.out.println("Vowel");
        }
        else {
            System.out.println("Consonent");
        }
    }
}

