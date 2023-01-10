using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace GCDAlgo
{
    internal class Program
    {
        static int GCD(int a, int b)
        {
            int temp;
            while((a%b)>0)
            { temp = a % b;
                a = b;
                b = temp;
            }

            return b;
        }
        static void Main(string[] args)
        {
            Console.Write("Enter 1st Integer: ");
            int FirstInteger = int.Parse(Console.ReadLine());
            Console.Write("Enter 2nd Integer: ");
            int SecondInteger = int.Parse(Console.ReadLine());
            Console.WriteLine("The Greatest Comon Divisor, GCD, is: " + GCD(FirstInteger, SecondInteger).ToString());
            Console.ReadKey();
        }
    }
}
