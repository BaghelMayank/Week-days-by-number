# Week-days-by-number
check week days by number , start from Number 0
using System;
using System.Collections.Generic;
using System.Text;

namespace smallest_number_find
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Enter Week Number:");
            int week = int.Parse(Console.ReadLine());
            
            switch (week)
            {
                case 0:
                    Console.WriteLine("Sunday");
                    break;
                case 1:
                    Console.WriteLine("Monday");
                    break;
                case 2:
                    Console.WriteLine("Tuesday");
                    break;
                case 3:
                    Console.WriteLine("Wednesday");
                    break;
                case 4:
                    Console.WriteLine("Thursday");
                    break;
                case 5:
                    Console.WriteLine("Friday");
                    break;
                case 6:
                    Console.WriteLine("Saturday");
                    break;
                default:
                    Console.WriteLine("Invalid Number, Please Try again");
                    break;
            }


            }
    }
}
