public class AssignmentOnMethod {

    // Q1. Create a class StudentInfo with a method displayInfo() that prints your name, age, and grade.
    public void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    // Q2. Create a class Calculator with a method addNumbers() that adds two numbers and prints the result.
    public void addNumbers() {
        int a = 15;
        int b = 25;
        int sum = a + b;
        System.out.println("Sum: " + sum);
    }

    // Q3. Create a class Greeting with a method sayHello() that takes your name as a parameter and prints:
    // Hello, Riya! Welcome to Java programming.
    // Replace "Riya" with your name.
    public void sayHello(String name) {
        System.out.println("Hello, " + name + "! Welcome to Java programming.");
    }

    // Q4. Create a class Circle with a method calculateArea() that calculates and prints the area of a circle.
    // Formula: Area = π × radius × radius, Use: radius = 7 and π = 3.14
    public void calculateArea() {
        double radius = 7;
        double pi = 3.14;
        double area = pi * radius * radius;
        System.out.println("Area of Circle: " + area);
    }

    // Q5. Create a class SimpleInterest with a method calculateInterest() that calculates simple interest.
    // Formula: SI = (P × T × R) / 100, Use values: P = 1000, T = 2 years, R = 5%
    public void calculateInterest() {
        double P = 1000;
        double T = 2;
        double R = 5;
        double SI = (P * T * R) / 100;
        System.out.println("Simple Interest: " + SI);
    }

    public static void main(String[] args) {
        AssignmentOnMethod obj = new AssignmentOnMethod();

        System.out.println("Q1 Output:");
        obj.displayInfo();

        System.out.println("\nQ2 Output:");
        obj.addNumbers();

        System.out.println("\nQ3 Output:");
        obj.sayHello("John");

        System.out.println("\nQ4 Output:");
        obj.calculateArea();

        System.out.println("\nQ5 Output:");
        obj.calculateInterest();
    }
}
