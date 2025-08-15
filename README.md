public class AssignmentOnMethod {

    // Q1
    public void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    // Q2
    public void addNumbers() {
        int a = 15;
        int b = 25;
        int sum = a + b;
        System.out.println("Sum: " + sum);
    }

    // Q3
    public void sayHello(String name) {
        System.out.println("Hello, " + name + "! Welcome to Java programming.");
    }

    // Q4
    public void calculateArea() {
        double radius = 7;
        double pi = 3.14;
        double area = pi * radius * radius;
        System.out.println("Area of Circle: " + area);
    }

    // Q5
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
