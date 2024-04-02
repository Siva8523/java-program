import java.util.Scanner;

public class SquareRoot {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter a perfect square number: ");
        if (scanner.hasNextInt()) {
            int number = scanner.nextInt();
            if (number >= 0) {
                double sqrt = Math.sqrt(number);
                System.out.println("Positive square root: " + sqrt);
                System.out.println("Negative square root: " + (-sqrt));
            } else {
                System.out.println("Please enter a non-negative perfect square number.");
            }
        } else {
            System.out.println("Invalid input. Please enter a valid integer.");
        }
        scanner.close();
    }
}
