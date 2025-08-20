# assignment-4
import java.util.Scanner;

public class QuadraticSolver {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Nhập hệ số a, b, c
        System.out.print("Enter coefficient a: ");
        double a = scanner.nextDouble();

        System.out.print("Enter coefficient b: ");
        double b = scanner.nextDouble();

        System.out.print("Enter coefficient c: ");
        double c = scanner.nextDouble();

        // Trường hợp đặc biệt: a = 0 → phương trình bậc nhất
        if (a == 0) {
            if (b == 0) {
                System.out.println("This is not an equation.");
            } else {
                double x = -c / b;
                System.out.println("This is a linear equation. The equation has one root: x = " + x);
            }
        } else {
            // Tính delta (Δ)
            double delta = b * b - 4 * a * c;

            if (delta < 0) {
                System.out.println("The equation has no real roots.");
            } else if (delta == 0) {
                double x = -b / (2 * a);
                System.out.println("The equation has a double root: x1 = x2 = " + x);
            } else {
                double sqrtDelta = Math.sqrt(delta);
                double x1 = (-b + sqrtDelta) / (2 * a);
                double x2 = (-b - sqrtDelta) / (2 * a);
                System.out.println("The equation has two distinct roots: x1 = " + x1 + " and x2 = " + x2);
            }
        }

        scanner.close();
    }
}

 
