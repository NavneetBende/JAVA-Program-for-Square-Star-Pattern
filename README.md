Printing Square Star Pattern
In this JAVA program we will be coding a star box pattern which will have n number of stars in it rows and n of stars in column hence it will be a n x n square star pattern  . The user will input a value, that will be used for determining the number of rows and columns of the pattern, and than we will use “for loop”, for printing stars at the desired places
Print Rhombus Star Pattern
Prerequisite:
Basic knowledge of Java language and loops

Algorithm:
Take number of rows as input from the user (length of side of the square) and store it in any variable (‘n‘ in this case).
Run a loop ‘i‘ number of times to iterate through the rows . From i=0 to i<n. The loop should be structured as for (int i = 0; i
Run a nested loop inside the previous loop to iterate through the columns. From j=0 to j<n The loop should be structured as                              for (int j=0 ; j
Print ‘*’ inside the nested loop to print ‘*’s in all the columns of a row.
Move to the next line by printing a new line. System.out.println();
Code in Java:
import java.util.Scanner;
public class Pattern1 {
    public static void main(String[] args) {

		Scanner sc = new Scanner(System.in);
		System.out.println("Enter no");
		int n = sc.nextInt();
		
		for (int i = 0; i<n ; i++) {
			for (int j=0 ; j<n ; j++) 
				System.out.print("*");
			System.out.println();
	     }
	 }
}

