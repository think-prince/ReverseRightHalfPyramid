# ReverseRightHalfPyramid
Java Code for Reverse Right Half Pyramid Patterns
import java.util.Scanner;

public class ReverseRightHalfPyramid {
    public static void main(String[] args) {
        System.out.println("Welcome to Print Pattern- Reverse Right Half Pyramid");
        Scanner input = new Scanner(System.in);
        System.out.println("Enter No. of Rows");
        int x = input.nextInt();
        int i=x;
        while(i>0){

            for (int j = 0; j < i; j++) {
                System.out.print("* ");


            }
            System.out.println();
            i--;

        }
    }
}

/*

*****
****
***
**
*

 */
