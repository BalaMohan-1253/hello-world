import java.util.Scanner;
public class Validage extends Exception
{
 public static void main(String args[])
 {
  while(true)
  {
  try
  {
   Scanner input = new Scanner(System.in);
   System.out.println("Enter your age: ");
   int age = input.nextInt();
   if(age>=18)
   {
    throw new Validage();
    }
   System.out.println("You are not eligible to vote");
   }
  catch(Invalid obj)
  {
   System.out.println("Congratulations! You are eligible to vote");
   }
  }
 }
}
