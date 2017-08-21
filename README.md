# Refactor-Volume-of-Pyramid
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Refactor_Volume_of_Pyramid
{
    class Program
    {
        static void Main(string[] args)
        {
            
            Console.Write("Length: ");

            double length = double.Parse(Console.ReadLine());

            Console.Write("Width: ");

            double width = double.Parse(Console.ReadLine());

            Console.Write("Height: ");

            double volume = double.Parse(Console.ReadLine());

            volume = (length * width * volume) / 3;

            Console.WriteLine("Pyramid Volume: {0:F2}", volume);
        }
    }
}
