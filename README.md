using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {

      Console.Write("Input number: ");
         int num1 = Convert.ToInt32(Console.ReadLine());
         Console.Write("Input the second number: ");
         int num2 = Convert.ToInt32(Console.ReadLine());
         Console.Write("Input the third number: ");
         int num3 = Convert.ToInt32(Console.ReadLine());
         if (num1 > num2 && num1 > num3)
         {
             Console.WriteLine("The 1st number is the greatest among three");
         }
         else if (num2 > num3 && num2 > num1)
         {
             Console.WriteLine("The 2nd number is the greatest among three");
         }
         else 
         {
             Console.WriteLine("The 3rd number is the greatest among three")
} 

} 



} 
