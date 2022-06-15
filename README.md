
import java.util.Scanner;
public class RectangleStat {
    public static void main (String[] arg){
	Scanner input =new Scanner (System.in);

	//input for the width
	System.out.print("Enter Width: ");
	//declaring variable for width
	double width = input.nextDouble();

	//input for the length
	System.out.print("Enter Length: ");
	//declaring variable for length
	double length =input.nextDouble();

	//need to declare variable to calculate the area
	double area = width * length;

	//need to declare variable to calculate the perimeter
	double perimeter = 2 *(width + length);

	//printing out the outcome
	System.out.println("When one side is " + width + "and the other side is " +length + ", the area is " + area + "and the perimeter is " + perimeter+ ".");
    }
}
