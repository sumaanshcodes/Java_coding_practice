# Java_coding_practice
A collection of Java programs for learning basic to advanced concepts. Mini Java projects and DSA problems implemented in Java. Core Java practice programs with explanations. 
Author - Sumansh Yadav
                  // Assignment on Methods


    // Q1. Create a class StudentInfo with a method displayInfo() that prints your name, age, and grade.


   public class StudentInfo {

    public void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    public static void main(String[] args) {
        StudentInfo obj = new StudentInfo();
        obj.displayInfo();
    }
}

    // Q2. Create a class Calculator with a method addNumbers() that adds two numbers and prints the result.

    
    public class Calculator {

    public void addNumbers() {
        int a = 10;
        int b = 20;
        int sum = a + b;
        System.out.println("Sum: " + sum);
    }

    public static void main(String[] args) {
        Calculator obj = new Calculator();
        obj.addNumbers();
    }
}

    //Q3. Create a class Greeting with a method sayHello() that takes your name as a parameter and prints: 



    public class Greeting {

    public void sayHello(String name) {
        System.out.println("Hello, " + name + "! Welcome to Java programming.");
    }

    public static void main(String[] args) {
        Greeting obj = new Greeting();
        obj.sayHello("John"); 
    }
}
   

    // Q4. Create a class Circle with a method calculateArea() that calculates and prints the area of a circle


    public class Circle {

    public void calculateArea() {
        double radius = 7;
        double pi = 3.14;
        double area = pi * radius * radius;
        System.out.println("Area of Circle: " + area);
    }

    public static void main(String[] args) {
        Circle obj = new Circle();
        obj.calculateArea();
    }
}
    
    // Q5. Create a class SimpleInterest with a method calculateInterest() that calculates simple interest.

    
   public class SimpleInterest {

    public void calculateInterest() {
        double P = 1000;
        double T = 2;
        double R = 5;
        double SI = (P * T * R) / 100;
        System.out.println("Simple Interest: " + SI);
    }

    public static void main(String[] args) {
        SimpleInterest obj = new SimpleInterest();
        obj.calculateInterest();
    }

