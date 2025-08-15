                  // Assignment on Methods
//                   import java.util.Scanner;
//                   public class Assignment {


                       //Q1. Create a class StudentInfo with a method displayInfo() that prints your name, age, and grade.


//        public void displayInfo() {
//            System.out.println("Name: Aman Sharma");
//            System.out.println("Age: 16");
//            System.out.println("Grade: 10th");
//        }
//
//        public static void main(String[] args) {
//            Assignment obj = new Assignment();
//            obj.displayInfo();
//        }

//Q2. Create a class Calculator with a method addNumbers() that adds two numbers and prints the result.


//        public void addNumbers() {
//            int a = 10;
//            int b = 20;
//            int sum = a + b;
//            System.out.println("Sum: " + sum);
//        }
//
//        public static void main(String[] args) {
//            Assignment obj = new Assignment();
//            obj.addNumbers();
//        }

//Q3. Create a class Greeting with a method sayHello() that takes your name as a parameter and prints:


//        public void sayHello(String name) {
//            System.out.println("Hello, " + name + "! Welcome to Java programming.");
//        }
//
//        public static void main(String[] args) {
//            Assignment obj = new Assignment();
//            obj.sayHello("John");
//        }

//


//Q4. Create a class Circle with a method calculateArea() that calculates and prints the area of a circle


//
//        public void calculateArea() {
//            double radius = 7;
//            double pi = 3.14;
//            double area = pi * radius * radius;
//            System.out.println("Area of Circle: " + area);
//        }
//
//        public static void main(String[] args) {
//            Assignment obj = new Assignment();
//            obj.calculateArea();
//        }
//


//
//Q5. Create a class SimpleInterest with a method calculateInterest() that calculates simple interest.


//        public void calculateInterest() {
//            double P = 1000;
//            double T = 2;
//            double R = 5;
//            double SI = (P * T * R) / 100;
//            System.out.println("Simple Interest: " + SI);
//        }
//
//        public static void main(String[] args) {
//            Assignment obj = new Assignment();
//            obj.calculateInterest();
//        }
//Q.6-Write a Java program to print all alphabets from a to z.
//
//    public static void main(String[] args) {
//        for (char c = 'a'; c <= 'z'; c++) {
//            System.out.print(c + " ");
//        }
//        System.out.println();
//        for (char c = 'A'; c <= 'Z'; c++) {
//            System.out.print(c + " ");
//        }
//
//  }
//
//
//                       public static void main(String[] args) {
//                           Scanner sc = new Scanner(System.in);
//                           System.out.print("Enter the number: ");
//                           int n = sc.nextInt();
//                           int count = 0;
//                           int temp = n;
//                           int sum = 0;
//
//                           // Count the number of digits
//                           int tempCount = n;
//                           while (tempCount != 0) {
//                               tempCount /= 10;
//                               count++;
//                           }
//
//                           // Calculate the sum of digits raised to the power of count
//                           int tempSum = n;
//                           while (tempSum != 0) {
//                               int digit = tempSum % 10;
//                               sum += Math.pow(digit, count);
//                               tempSum /= 10;
//                           }
//
//                           // Check if the number is an Armstrong number
//                           if (sum == temp) {
//                               System.out.println("Armstrong");
//                           } else {
//                               System.out.println("Not Armstrong");
//                           }
//                       }
//                   }



