# zahin-chowdhury--demo
This is my first Git repository.
<br>
Author-Zahin chowdhury
public class ArrayOperations {
    public static void main(String[] args) {
        // Task 1: Add, multiply, subtract two numbers
        int num1 = 5, num2 = 3;
        System.out.println("Addition: " + (num1 + num2));
        System.out.println("Multiplication: " + (num1 * num2));
        System.out.println("Subtraction: " + (num1 - num2));

        // Task 2: Define the array
        int[] a = {10, 15, 20, 25, 30};

        // Task 3: Find the sum and average of the array elements using a loop
        int sum = 0;
        for (int value : a) {
            sum += value;
        }
        double average = (double) sum / a.length;
        System.out.println("Sum of array elements: " + sum);
        System.out.println("Average of array elements: " + average);

        // Task 4: Find the even numbers in the array
        System.out.print("Even numbers: ");
        for (int value : a) {
            if (value % 2 == 0) {
                System.out.print(value + " ");
            }
        }
        System.out.println();

        // Task 5: Find the odd numbers in the array
        System.out.print("Odd numbers: ");
        for (int value : a) {
            if (value % 2 != 0) {
                System.out.print(value + " ");
            }
        }
        System.out.println();

        // Task 6: Find the sum of odd numbers
        int sumOdd = 0;
        for (int value : a) {
            if (value % 2 != 0) {
                sumOdd += value;
            }
        }
        System.out.println("Sum of odd numbers: " + sumOdd);

        // Task 7: Find the sum of even numbers
        int sumEven = 0;
        for (int value : a) {
            if (value % 2 == 0) {
                sumEven += value;
            }
        }
        System.out.println("Sum of even numbers: " + sumEven);

        // Task 8: Print the multiplication table of 12
        System.out.println("Multiplication table of 12:");
        for (int i = 1; i <= 10; i++) {
            System.out.println("12 x " + i + " = " + (12 * i));
        }

        // Task 9: Function of power
        int base = 2, exponent = 3;
        int power = 1;
        for (int i = 1; i <= exponent; i++) {
            power *= base;
        }
        System.out.println(base + " raised to the power of " + exponent + " is: " + power);
    }
}