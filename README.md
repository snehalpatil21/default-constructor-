# default-constructor-
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace constructor89
{
    class Program
    {
        //c# program to illustrate calling
        //a default constructor
        int num;
        string name;
        //this would be invoked while the object of class created.
        Program()
        {
            num = 10;
            name = "snehal";
            Console.WriteLine("hello");
        }
        //main method
        static void Main(string[] args)
        {
            //this would invoke default  //constructor.
            Program p = new Program();
            //default constructor provides //the default values to the //int and object.
            Console.WriteLine(p.name);
            Console.WriteLine(p.num);
            Console.ReadLine();
        }
    }
}
