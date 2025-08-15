public class AssignmentOnMethod {

    // Q1. Print Student Info
    public void displayInfo() {
        System.out.println("Name: Aman Sharma");
        System.out.println("Age: 16");
        System.out.println("Grade: 10th");
    }

    // Q2. Add Two Numbers
    public void addNumbers() {
        int a = 15;
        int b = 25;
        int sum = a + b;
        System.out.println("Sum: " + sum);
    }

    // Q3. Greeting Message
    public void sayHello(String name) {
        System.out.println("Hello, " + name + "! Welcome to Java programming.");
    }

    // Q4. Area of Circle
    public void calculateArea() {
        double radius = 7;
        double pi = 3.14;
        double area = pi * radius * radius;
        System.out.println("Area of Circle: " + area);
    }

    // Q5. Simple Interest
    public void calculateInterest() {
        double P = 1000;
        double T = 2;
        double R = 5;
        double SI = (P * T * R) / 100;
        System.out.println("Simple Interest: " + SI);
    }

    // Q6. Armstrong Number
    public void checkArmstrong(int num) {
        int original = num;
        int sum = 0;
        while (num > 0) {
            int digit = num % 10;
            sum += digit * digit * digit;
            num /= 10;
        }
        if (sum == original) {
            System.out.println(original + " is an Armstrong number.");
        } else {
            System.out.println(original + " is not an Armstrong number.");
        }
    }

    // Q7. Palindrome Number
    public void checkPalindrome(int num) {
        int original = num;
        int reversed = 0;
        while (num > 0) {
            int digit = num % 10;
            reversed = reversed * 10 + digit;
            num /= 10;
        }
        if (reversed == original) {
            System.out.println(original + " is a Palindrome number.");
        } else {
            System.out.println(original + " is not a Palindrome number.");
        }
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

        System.out.println("\nQ6 Output:");
        obj.checkArmstrong(153);

        System.out.println("\nQ7 Output:");
        obj.checkPalindrome(121);
    }
}
