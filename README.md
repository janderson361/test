# test
package gradecalculator;

import java.util.Scanner;

/**
 * @author Dawn Susee
 * This program ask the user to enter three test grades. The average is 
 * calculated and then the test grades and the average is printed to the screen.
 */

public class GradeCalculator {

    public static void main(String[] args) {
        // Define variables
        int test1, test2, test3;
        double average;
        
        Scanner scan = new Scanner(System.in);
        
        // Get input from user
	System.out.println("Enter your score for test 1");
	test1 = scan.nextInt();
	System.out.println("Enter your score for test 2");
	test2 = scan.nextInt();
	System.out.println("Enter your score for test 3");
	test3 = scan.nextInt();

        // Calculate average
        average = (test1 + test2 + test3) / 3;

        // Print the grades and average for the user
        System.out.println("Test 1 = " + test1);
        System.out.println("Test 2 = " + test2);
        System.out.println("Test 3 = " + test3);
        System.out.println("The average is: " + average);
    }
    
}
