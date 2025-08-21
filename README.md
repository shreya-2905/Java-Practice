import java.util.*;
public class Calculator {
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the value of a");
        int a = sc.nextInt();
        System.out.println("Enter the value of b");
        int b = sc.nextInt();
        int sum = a + b;
        int mul = a * b;
        System.out.println("Enter your choice");
        int c = sc.nextInt(); 
        
       
        if(c == 1){
            System.out.println("The sum of two number is : " + sum);
        }
        else if(c == 2){
            System.out.println("The mul of two number is : " + mul);
        }
        else{
            System.out.println("blank");
        }
  }
 }


































