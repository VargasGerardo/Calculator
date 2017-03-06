# Calculator
import java.util.Scanner;


public class Operators {

	public static void main(String[] args) {
	Scanner calculator = new Scanner (System.in);
	double fnum, snum, answer; //These are the variables
	System.out.println("Enter first number: ");
	fnum = calculator.nextDouble();
	System.out.println("Enter second number: ");
	snum = calculator.nextDouble();
	answer = fnum + snum;
	System.out.println(answer);
	
	System.out.println("Enter first number: ");
	fnum = calculator.nextDouble();
	System.out.println("Enter second number: ");
	snum = calculator.nextDouble();
	answer = fnum - snum;
	System.out.println(answer);
	
	System.out.println("Enter first number: ");
	fnum = calculator.nextDouble();
	System.out.println("Enter second number: ");
	snum = calculator.nextDouble();
	answer = fnum * snum;
	System.out.println(answer);
	
	System.out.println("Enter first number: ");
	fnum = calculator.nextDouble();
	System.out.println("Enter second number: ");
	snum = calculator.nextDouble();
	answer = fnum / snum;
	System.out.println(answer);
	//*This is my first Calculator that only stores 2 numbers and
	//adds, subtracts, 
	//multiplies, and divides in that order*//

	}

}
