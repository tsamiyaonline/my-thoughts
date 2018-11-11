# my-thoughts
import java.util.Scanner;
public class BmiCalculator {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        //Create scanner       
        // TODO code application logic here{
         Scanner Bmicalculator = new Scanner (System.in);
        //Declare Variables
        double Weight, Height, BMI;
        //Prompt User
        System.out.println("Enter weight in Kg");
                Weight = Bmicalculator.nextDouble();
        System.out.println("Enter Height in cm");
                Height = Bmicalculator.nextDouble();
                BMI = Weight*10000/(Height*Height);
        System.out.println("The BMI = "+ BMI);
    }
    
}
