//import stuff here
import java.util.Scanner; 
public class program7 {
    public static void main (String[]args) {
        int newStanley = 0; 
        Scanner myScanner = new Scanner(System.in); 
        System.out.println("Enter Schrute-Bucks: "); 
        int schrute = myScanner.nextInt(); 
        System.out.println("Enter Klevins: "); 
        int klevin = myScanner.nextInt(); 
        System.out.println("Enter Stanley-Nickels: "); 
        int oldStanley = myScanner.nextInt(); 
        final double stanleyInSchrute = 240.0;
        final double klevinsInSchrute = 20.0; 
        final double stanleyInKlevin = 12.0; 
        double answer1 = ((stanleyInKlevin * klevin + oldStanley)/stanleyInSchrute)+schrute;
        double answerFinal = ((int)((answer1 + 0.005) * 100)) / 100.0;
        System.out.println("Decimal schrute-bucks: $" + answerFinal);
        
    }
}
//Your code here

//Paste console output below:
/*
Enter Schrute-Bucks: 
7
Enter Klevins: 
17
Enter Stanley-Nickels: 
9
Decimal schrute-bucks: $7.89

*/
