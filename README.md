# Java-code-Handling-exception-

import java.util.InputMismatchException;

import java.util.Scanner;

public class ExceptionHandlingExample {

V

V

public static void main(String[]

args) {

Scanner input = new

Scanner(System.in);

int a, b;

try {

System.out.print("Enter the value of

'a': ");

a = input.nextInt();

K System.out.print("Enter the

value of 'b': ");

→b = input.nextInt();

→→System.out.println("Result

of a/b: " + divide(a,b));

V

{ } catch (ArithmeticException e)

System.out.print("Arithmetic Exception:

/ by zero\n");

V

} catch (InputMismatchException

e) {

System.out.println("Input

Mismatch Exception: Please enter valid

integer values.");

V

}

input.close();

}

public static int divide(int a, int

}

b) {

return a / b;