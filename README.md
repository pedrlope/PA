# PA
(programação de aplicativos)

# Aula 1

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Pedroc2080
{
    internal class Program
    { 
            static void Main(string[] args)
        {
            double cabelo; 
                string mewing, capoeira, cachorro;
                bool boo, booo, bo, bu;


            Console.WriteLine("quanto de cabelo vc tem?");
             cabelo = double.Parse(Console.ReadLine());
            Console.WriteLine("vc faz capoeira?");
            capoeira = (Console.ReadLine());
            Console.WriteLine("vc faz mewing?");
            mewing = (Console.ReadLine());
            Console.WriteLine("vc sabe oq o cachorro esta fazendo?");
            cachorro = (Console.ReadLine());
            if (cabelo == 0)
            {
                boo = true;
            }
            else
            {
                boo = false;
            }

            if (capoeira == "não")
            {
                booo = true;
            }
            else
            {
                booo = false;
            }

            if (mewing == "não")
            {
                bo = true;
            }
            else
            {
                bo = false;
            }

            if (cachorro == "não")
            {
                bu = true;
            }
            else
            {
                bu = false;
            }

            if (boo == true && bu == true && bo == true && booo == true)
                {
                    Console.WriteLine($"vc é feio, já que vc tem {cabelo} decabelo");
                    Console.WriteLine("além que vc não faz mewing");
                    Console.WriteLine("nao luta capoeira");
                    Console.WriteLine("e nao sabe o que o cachorro está fazendo"); 
            }

            if(boo == true && bu == false && bo == false && booo == true)
                {
                Console.WriteLine($"vc é mediano, já que vc tem {cabelo} de cabelo");
                Console.WriteLine("vc faz mewing");
                Console.WriteLine("vc luta capoeira");
                Console.WriteLine("e nao sabe o que o cachorro está fazendo");
            }

            if(boo == false && bu == false && bo == false && booo == false)
                {
                Console.WriteLine($"vc é perfeito, já que vc tem {cabelo} de cabelo");
                Console.WriteLine("vc faz mewing");
                Console.WriteLine("vc luta capoeira");
                Console.WriteLine("e sabe o que o cachorro está fazendo");
            }

            if (boo == true && bu == true && bo == true && booo == false)
            {
                Console.WriteLine($"vc é furry, já que vc tem {cabelo} de cabelo");
                Console.WriteLine("vc nao faz mewing");
                Console.WriteLine("vc nao luta capoeira");
                Console.WriteLine("e sabe o que o cachorro está fazendo");
            }


           
        }
        }
    }
