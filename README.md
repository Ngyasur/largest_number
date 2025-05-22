# largest_number
3rd problem
 

import java.util.Scanner; 
 
public class Largest_number { 
    public static void main(String[] args) { 
        Scanner num = new Scanner(System.in); 
        System.out.println("Enter a number you want to check: "); 
        int a = num.nextInt(); 
        int b = num.nextInt(); 
        int c = num.nextInt(); 
        if (a>b && a>c){ 
            System.out.println("a is the largest number: "); 
        } 
        else if (b>a && a>c){ 
            System.out.println("b is the largest number: "); 
        } 
        else{ 
            System.out.println("c is the largest number"); 
        } 
    } 
}
