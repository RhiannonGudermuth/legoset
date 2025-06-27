using System;
using System.Collections.Generic;

// file name 
namespace LegoSetNew
{
    // create a new class
    class LegoSet
    {
        // create fields (type of class member)
        public string name;
        public int teileanzahl;
    }

    // class functions in Program.cs
    class Program
    {
        //puts following code in the main method (entry point)
        static void Main(string[] args)
        {

            //add the following classes to a list 

            // instance of a class
            LegoSet l0 = new LegoSet();
            l0.name = "Hagrids Hütte";
            l0.teileanzahl = 896;

            LegoSet l1 = new LegoSet();
            l1.name = "Dobby der Hauself";
            l1.teileanzahl = 403;

            LegoSet l2 = new LegoSet();
            l2.name = "der Sprechende Hut";
            l2.teileanzahl = 561;

            // Have it printed to console in following format "LEGO Set: name - teileanzahl"

            Console.WriteLine(l0.name);
            Console.WriteLine(l0.teileanzahl);

            Console.WriteLine(l1.name);
            Console.WriteLine(l1.teileanzahl);

            Console.WriteLine(l2.name);
            Console.WriteLine(l2.teileanzahl);

        }




        // Console.ReadLine("Willst du ein weiteres Set hinzufügen? ja oder nein")

        // string answer = "ja";

        // if (answer == "ja")
        // {
        //      take the answer typed into the terminal and have 
        //      it be added to the list 
        //      make a list and use the Add.(//) fkt

        //     Console.WriteLine(l0.name);


        //     Console.WriteLine(l0.teileanzahl);

        //     Console.WriteLine(l1.name);
        //     Console.WriteLine(l1.teileanzahl);

        //     Console.WriteLine(l2.name):
        //     Console.WriteLine(l2.teileanzahl);

        //  }

        //     Programm beenden

    }
}
