# nerimanalt-nok
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication25
{
    class Program
    {
        static void Main(string[] args)
        {
            string isim;
            Console.WriteLine("ad giriniz");
            isim = Console.ReadLine();
            foreach (char a in (isim))
            {
                Console.Write((char)(a + 10));
            }
            Console.ReadKey();
        }
    }
}
