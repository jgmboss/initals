# import java.util.Scanner;
public class initials
{
    public static void main (String args[]){
        Scanner input = new Scanner (System.in);
        System.out.println ("Please enter your first name");
        String first = input.nextLine();
        System.out.println ("Please enter your middle name");
        String middle = input.nextLine();
        System.out.println ("Please enter your last name");
        String last = input.nextLine();
        
        System.out.print (first.substring(0,1)); 
        System.out.print (middle.substring(0,1));
        System.out.println (last.substring(0,1));
       
     
}
}
