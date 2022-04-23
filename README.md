# first-3-even-number-in-for-loop-
using System;
using System.Linq;
using System.Collections.Generic;
namespace HelloWorld
{
    public class Program 
    {
        public static void Main()
        {
			int i;
			int n;
			Console.WriteLine("Enter a number:-");
		    n=Convert.ToInt32(Console.ReadLine());
		    Console.WriteLine("first 3 even numbers of given number in for loop:-");
		     for(i=1;i<=6;i++)
		    {
		        {
		    	if(i%2==0)
		    	{
		    	Console.WriteLine(i);
		        }
		       }
		    }
		    Console.ReadLine();
        }
    }
}
