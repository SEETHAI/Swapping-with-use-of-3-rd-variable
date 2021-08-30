# Swapping-with-use-of-3-rd-variable
Java program to Swap two variables using of third variable
import java.util.Scanner;  

class Swap_With {  

    public static void main(String[] args) {  

       int x, y, temp;   

       Scanner input = new Scanner(System.in);  

       System.out.println("Enter the value of X and Y");  

       x = input.nextInt();  

       y = input.nextInt();  

       System.out.println("Before swapping numbers: "+x +"  "+ y);  

       temp = x;  

       x = y;  

       y = temp;  

       System.out.println("After swapping: "+x +"   " + y);  

       System.out.println( );  

    }    

}  
