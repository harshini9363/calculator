import java.util.Scanner;
public class Main{
    public static void main(String[]args){
        float num1,num2,num3;
        Scanner scanner=new Scanner(System.in);
        System.out.println("simple calculator");
        System.out.println("1.Addition");
        System.out.println("2.subtraction");
        System.out.println("3.Multiplication");
        System.out.println("4.Division");
        System.out.println("enter your choice");
        int op= scanner.nextInt();
        System.out.println("enter the first number");
        num1= scanner.nextInt();
        System.out.println("enter the second number");
        num2= scanner.nextInt();
        
        switch(op){
            case 1 :
            num3=num1+num2;
            System.out.println("Addition:"+num3);
            break;
            case 2 :
            num3=num1-num2;
            System.out.println("Subtraction:"+num3);
            break;
            case 3 :
            num3=num1*num2;
            System.out.println("Multiplication:"+num3);
            break;
            case 4 :
            num3=num1%num2;
            System.out.println("Division:"+num3);
            break;
            
            
        }
        scanner.close();
         }
}
