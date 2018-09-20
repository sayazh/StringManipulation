# StringManipulation
Substring1
import java.util.Scanner;

public class Substring1 {
    public static void main(String[] args) {
		
    	 // Ask user to enter a word. 
    	//If the work contains starts with x, print the word without x.
    	//Input:
    	//xcode
    	// Output: 
    	//code
    	
    	Scanner scan = new Scanner(System.in);
    	System.out.println("Enter please any word");
    	String word = scan.nextLine();
    	
    	if (word.charAt(0)=='x') {
			System.out.println(word.replace("x" ,""));	
    	} else {
    		System.out.println("This word does not have the letter 'x'");
    	}
    	scan.close();
	}
}
