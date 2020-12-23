# votingchecker
#Votingchecker is program where we can check the age of voter either he/she eligible for vote or not.
import java.util.Scanner;
public class votingchecker {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
  
		Scanner a = new Scanner(System.in);
		String name = a.nextLine();
		System.out.println("Hii"+ " "+ name );
		System.out.println("Enter your Email id:-" );
		String Email  = a.nextLine();
		
		
		
		System.out.println("Enter your age:-");
		int age = a.nextInt();
		if (age >= 18) {
			
			System.out.println("You can vote now" );
		} else {
			System.out.println("You cannot vote now");
		}
	}

}
