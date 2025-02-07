using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace Currency_Converter
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("\n\n\t\t\t\t*-*-*-*-*-*-*-*Currency Converter*-*-*-*-*-*-*-*");
            Console.WriteLine("\n\n\t\tCheck Currency Value in Your Country and Convert ");
            Console.WriteLine("\n\n\t\t1.India INR          \t2.United States Dollar");
            Console.WriteLine("\n\t\t3.Euro EUR             \t4.Japanes Yen JPY");
            Console.WriteLine("\n\t\t5.British Pound GBP    \t6.Australian Dollar AUD");
            Console.WriteLine("\n\t\t7.Canadian Dollar CAD");
            int exit = 1;
            while (exit == 1)
            {
                int Country;
                Console.Write("\n\t\tEnter Country Number : ");
                Country = Convert.ToInt32(Console.ReadLine());
                if (Country == 1)
                {
                    Console.WriteLine("\n\t\tAll Currency values in INR");
                    Console.WriteLine("\n\t\t1. 1(USD)= 75 INR    \t2. 1(EUR)= 83 INR");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 0.86 INR  \t4. 1(GBP)= 99 INR");
                    Console.WriteLine("\n\t\t5. 1(AUD)= 54 INR   \t6. 1(CAD)= 58 INR");

                    Console.WriteLine("\n\t\tChoose Currency Number to Convert in CAD");
                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double usdRate = 75;
                        
                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double usdAmount = INR / usdRate;
                        Console.WriteLine("\n\t\tINR Rate In USD: "+usdAmount+" Dollar");
                    }
                    if (opt == 2)
                    {
                        double eurRate = 83;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double eurAmount = INR / eurRate;
                        Console.WriteLine("\n\t\tINR Rate In EUR: " + eurAmount + " Euro");
                    }
                    if (opt == 3)
                    {
                        double jpyRate = 0.86;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = INR / jpyRate;
                        Console.WriteLine("\n\t\tINR Rate In JPY: " + jpyAmount + " Yen");
                    }
                    if (opt == 4)
                    {
                        double gbpRate = 99;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = INR / gbpRate;
                        Console.WriteLine("\n\t\tINR Rate In GBP: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 54;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double audAmount = INR / audRate;
                        Console.WriteLine("\n\t\tINR Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double cadRate = 58;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double INR = Convert.ToDouble(Console.ReadLine());

                        double cadAmount = INR / cadRate;
                        Console.WriteLine("\n\t\tINR Rate In CAD: " + cadAmount + " Dollar");
                    }
                }
                /*----------------------------------------------------------------------------------------------------------*/
                if (Country == 2)
                {
                    Console.WriteLine("\n\t\tAll Currency values in USD");
                    Console.WriteLine("\n\t\t1. 1(INR)= 0.013 USD    \t2. 1(EUR)= 1.10 USD");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 0.0091 USD   \t4. 1(GBP)= 1.31 USD");
                    Console.WriteLine("\n\t\tn5. 1(AUD)= 0.74 USD    \t6. 1(CAD)= 0.80 USD");

                    Console.WriteLine("\n\t\tChoose Currency Number to Convert in JPY");

                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double inrRate = 0.013;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double inrAmount = USD / inrRate;
                        Console.WriteLine("\n\t\tUSD Rate In INR: " + inrAmount + " Dollar");
                    }
                    if (opt == 2)
                    {
                        double eurRate = 1.10;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double eurAmount = USD / eurRate;
                        Console.WriteLine("\n\t\tUSD Rate In EUR: " + eurAmount + " Euro");
                    }
                    if (opt == 3)
                    {
                        double jpyRate = 0.0091;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = USD / jpyRate;
                        Console.WriteLine("\n\t\tUSD Rate In JPY: " + jpyAmount + " Yen");
                    }
                    if (opt == 4)
                    {
                        double gbpRate = 1.31;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = USD / gbpRate;
                        Console.WriteLine("\n\t\tUSD Rate In GBP: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 0.74;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double audAmount = USD / audRate;
                        Console.WriteLine("\n\t\tUSD Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double cadRate = 0.80;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double USD = Convert.ToDouble(Console.ReadLine());

                        double cadAmount = USD / cadRate;
                        Console.WriteLine("\n\t\tUSD Rate In CAD: " + cadAmount + " Dollar");
                    }
                }

                /*----------------------------------------------------------------------------------------------------------*/
                
                if (Country == 3)
                {
                    Console.WriteLine("\n\t\tAll Currency values in EUR");
                    Console.WriteLine("\n\t\t1. 1(USD)= 0.91 EUR    \t2. 1(INR)= 0.011 EUR");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 0.0082 EUR  \t4. 1(GBP)= 1.18 EUR");
                    Console.WriteLine("\n\t\tn5. 1(AUD)= 0.65 EUR   \t6. 1(CAD)= 0.69 EUR");

                    Console.WriteLine("\n\t\tChoose Currency Number to Convert in EUR");

                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double inrRate = 0.91;

                        Console.Write("\n\n\t\tEnter the Amount in EUR: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double inrAmount = EUR / inrRate;
                        Console.WriteLine("\n\t\tEUR Rate In INR: " + inrAmount + " Euro");
                    }
                    if (opt == 2)
                    {
                        double inrRate = 0.011;

                        Console.Write("\n\n\t\tEnter the Amount in USD: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double inrAmount = EUR / inrRate;
                        Console.WriteLine("\n\t\tEUR Rate In INR: " + inrAmount + " Rupee");
                    }
                    if (opt == 3)
                    {
                        double jpyRate = 0.0082;

                        Console.Write("\n\n\t\tEnter the Amount in EUR: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = EUR / jpyRate;
                        Console.WriteLine("\n\t\tEUR Rate In JPY: " + jpyAmount + " Yen");
                    }
                    if (opt == 4)
                    {
                        double gbpRate = 1.18;

                        Console.Write("\n\n\t\tEnter the Amount in EUR: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = EUR / gbpRate;
                        Console.WriteLine("\n\t\tEUR Rate In GBP: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 0.65;

                        Console.Write("\n\n\t\tEnter the Amount in EUR: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double audAmount = EUR / audRate;
                        Console.WriteLine("\n\t\tEUR Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double cadRate = 0.69;

                        Console.Write("\n\n\t\tEnter the Amount in EUR: ");
                        double EUR = Convert.ToDouble(Console.ReadLine());

                        double cadAmount = EUR / cadRate;
                        Console.WriteLine("\n\t\tEUR Rate In CAD: " + cadAmount + " Dollar");
                    }
                }

                /*----------------------------------------------------------------------------------------------------------*/

                if (Country == 4)
                {
                    Console.WriteLine("\n\t\tAll Currency values in JPY");
                    Console.WriteLine("\n\t\t1. 1(USD)= 113.99 JPY   \t2. 1(EUR)= 129.86 JPY");
                    Console.WriteLine("\n\t\t3. 1(INR)= 1.36 JPY     \t4. 1(GBP)= 150.97 JPY");
                    Console.WriteLine("\n\t\tn5. 1(AUD)= 83.01 JPY   \t6. 1(CAD)= 88.51 JPY");

                    Console.WriteLine("\n\t\tChoose Currency Number to Convert in JPY");

                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double inrRate = 113.99;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double inrAmount = JPY / inrRate;
                        Console.WriteLine("\n\t\tJPY Rate In INR: " + inrAmount + " Euro");
                    }
                    if (opt == 2)
                    {
                        double eurRate = 129.86;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double eurAmount = JPY / eurRate;
                        Console.WriteLine("\n\t\tJPY Rate In EUR: " + eurAmount + " Euro");
                    }
                    if (opt == 3)
                    {
                        double inrRate = 1.36;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = JPY / inrRate;
                        Console.WriteLine("\n\t\tJPY Rate In INR: " + jpyAmount + " Yen");
                    }
                    if (opt == 4)
                    {
                        double gbpRate = 150.97;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = JPY / gbpRate;
                        Console.WriteLine("\n\t\tJPY Rate In GBP: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 83.01;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double audAmount = JPY / audRate;
                        Console.WriteLine("\n\t\tJPY Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double cadRate = 88.51;

                        Console.Write("\n\n\t\tEnter the Amount in JPY: ");
                        double JPY = Convert.ToDouble(Console.ReadLine());

                        double cadAmount = JPY / cadRate;
                        Console.WriteLine("\n\t\tJPY Rate In CAD: " + cadAmount + " Dollar");
                    }
                }

                /*----------------------------------------------------------------------------------------------------------*/

                if (Country == 5)
                {
                    Console.WriteLine("\n\t\tAll Currency values in GBP");
                    Console.WriteLine("\n\t\t1. 1(USD)= 0.76 GBP    \t2. 1(EUR)= 0.85 GBP");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 0.0066 GBP  \t4. 1(INR)= 0.0075 GBP");
                    Console.WriteLine("\n\t\t5. 1(AUD)= 0.55 GBP    \t6. 1(CAD)= 0.59 GBP");

                    Console.WriteLine("\n\t\tChoose Currency Number to Convert in GBP");

                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double usdRate = 0.76;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double usdAmount = GBP / usdRate;
                        Console.WriteLine("\n\t\tGBP Rate In INR: " + usdAmount + " Euro");
                    }
                    if (opt == 2)
                    {
                        double eurRate = 0.85;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double eurAmount = GBP / eurRate;
                        Console.WriteLine("\n\t\tGBP Rate In EUR: " + eurAmount + " Euro");
                    }
                    if (opt == 3)
                    {
                        double inrRate = 0.0066;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = GBP / inrRate;
                        Console.WriteLine("\n\t\tGBP Rate In INR: " + jpyAmount + " Yen");
                    }
                    if (opt == 4)
                    {
                        double inrRate = 0.0075;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = GBP / inrRate;
                        Console.WriteLine("\n\t\tGBP Rate In INR: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 0.55;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double audAmount = GBP / audRate;
                        Console.WriteLine("\n\t\tGBP Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double cadRate = 0.59;

                        Console.Write("\n\n\t\tEnter the Amount in GBP: ");
                        double GBP = Convert.ToDouble(Console.ReadLine());

                        double cadAmount = GBP / cadRate;
                        Console.WriteLine("\n\t\tJPY Rate In CAD: " + cadAmount + " Dollar");
                    }
                }

                /*----------------------------------------------------------------------------------------------------------*/

                if (Country == 6)
                {
                    Console.WriteLine("\n\t\tAll Currency values AUD");
                    Console.WriteLine("\n\t\t1. 1(USD)= 1.36 AUD     \t2. 1(EUR)= 1.53 AUD");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 0.012 AUD    \t4. 1(GBP)= 1.79 AUD");
                    Console.WriteLine("\n\t\tn5. 1(INR)= 0.018 AUD   \t6. 1(CAD)= 0.92 AUD");

                    Console.WriteLine("\n\t\tChoose Number to Convert in AUD");
                }

                /*-----------------------------------------------------------------------------------------------------*/

                if (Country == 7)
                {
                    Console.WriteLine("\n\t\tAll Currency values in CAD");
                    Console.WriteLine("\n\t\t1. 1(USD)= 1.18 CAD    \t2. 1(EUR)= 1.35 CAD");
                    Console.WriteLine("\n\t\t3. 1(JPY)= 88.51 CAD   \t4. 1(GBP)= 1.49 CAD");
                    Console.WriteLine("\n\t\tn5. 1(AUD)= 1.00 CAD   \t6. 1(INR)= 0.018 CAD");

                    Console.WriteLine("\n\t\tChoose Number to Convert in CAD");
                    
                    int opt;
                    Console.Write("\n\n\t\tEnter Number to Convert: ");
                    opt = Convert.ToInt32(Console.ReadLine());

                    if (opt == 1)
                    {
                        double usdRate = 1.18;

                        Console.Write("\n\n\t\tEnter the Amount in CAD: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double usdAmount = CAD / usdRate;
                        Console.WriteLine("\n\t\tCAD Rate In USD: " + usdAmount + " Dollar");
                    }
                    if (opt == 2)
                    {
                        double eurRate = 1.35;

                        Console.Write("\n\n\t\tEnter the Amount in CAD: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double eurAmount = CAD / eurRate;
                        Console.WriteLine("\n\t\tCAD Rate In EUR: " + eurAmount + " Euro");
                    }
                    if (opt == 3)
                    {
                        double jpyRate = 88.51;

                        Console.Write("\n\n\t\tEnter the Amount in CAD: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double jpyAmount = CAD / jpyRate;
                        Console.WriteLine("\n\t\tCAD Rate In JPY: " + jpyAmount + " JPY");
                    }
                    if (opt == 4)
                    {
                        double gbpRate = 1.49;

                        Console.Write("\n\n\t\tEnter the Amount in CAD: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double gbpAmount = CAD / gbpRate;
                        Console.WriteLine("\n\t\tINR Rate In GBP: " + gbpAmount + " Pound");
                    }
                    if (opt == 5)
                    {
                        double audRate = 1.00;

                        Console.Write("\n\n\t\tEnter the Amount in INR: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double audAmount = CAD / audRate;
                        Console.WriteLine("\n\t\tCAD Rate In AUD: " + audAmount + " Dollar");
                    }
                    if (opt == 6)
                    {
                        double inrRate = 0.018;

                        Console.Write("\n\n\t\tEnter the Amount in CAD: ");
                        double CAD = Convert.ToDouble(Console.ReadLine());

                        double inrAmount = CAD / inrRate;
                        Console.WriteLine("\n\t\tCAD Rate In INR: " + inrAmount + " Rupee");
                    }
                }
                Console.Write("\n\n\t\tIf You Want to Repeat the Program Enter 1 else Enter Key:- ");
                exit = Convert.ToInt32(Console.ReadLine());
            }
            Console.ReadKey();
        }
    }
}