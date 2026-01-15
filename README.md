# -PF-Assignment
Qno. 8

// Online Java Compiler
// Use this editor to write, compile and run your Java code online

    import java.util.Scanner;

public class TriangleArea {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // Fixed values
        double a = 5;
        double b = 6;
        double c = 7;

        double s = (a + b + c) / 2;
        double area = Math.sqrt(s * (s - a) * (s - b) * (s - c));

        System.out.println("Side a = " + a);
        System.out.println("Side b = " + b);
        System.out.println("Side c = " + c);
        System.out.println("Area of Triangle = " + area);

        sc.close();
    }
}
