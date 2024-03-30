using System;
class Program
{
    public static void Main(string[] args)
    {
        Console.WriteLine("                                                         BUS TICKET GENERATION ");
        Console.WriteLine("------------------------------------------------------------------------------------------------------------------------");
        Console.Write("Bus Depo Number          : ");
        string d=Console.ReadLine();
        Console.Write("Date in format dd/mm/yy : ");
        string dd = Console.ReadLine();
        Console.Write("Source of Journey        : ");
        string s = Console.ReadLine();
        Console.Write("Destination of Journey   : ");
        string de = Console.ReadLine();
        Console.Write("No of adults             : ");
        int n =Convert.ToInt32(Console.ReadLine());

        Console.Write("No of Children           : ");
        int c = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine();
        Console.WriteLine("-------------------------APSRTC----------------------");
        Console.WriteLine("                                                   ");
        Console.WriteLine("Bus Depo Number :"+d+"                             ");
        Console.WriteLine("Date            :"+dd+"                            ");
        Console.WriteLine("From Source "+s+" to Destination "+de+"            ");
        Console.WriteLine("                                                   ");
        Console.WriteLine("            A : "+n+" X"+" 40 = "+(n*40)+"         ");
        Console.WriteLine("            C : "+c+" X"+" 20 = "+(c*20)+"         ");
        Console.WriteLine("                                                   "); 
        Console.WriteLine("           Total amount Rupees Rs = "+((n*40)+(c*20)));
        Console.WriteLine();
        Console.WriteLine("                Have a nice journey                ");
        Console.WriteLine();
        Console.WriteLine("                 NON TRANSFERABLE                  ");
        Console.WriteLine();
        Console.WriteLine("-----------------------------------------------------");
    }
}
