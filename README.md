# Array-Sum-Java_interview_practice
Java program to get the sum of given array
package arraysum;

/**
 *
 * @author Dinesh Nanda
 */

public class ArraySum {

    public static void main(String[] args) {
        
        int arr [] = {4, 8, 2, 1, 9};
        
        int sum =0;
        
        for(int i = 0; i < arr.length; i++){
            sum = sum + arr[i];
        }
        System.out.println("The sum of given array is: "+ sum);
    }
}
