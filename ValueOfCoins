using System;

public class ValueOfCoins
{
    public static void Main()
    {
        //instance variables
        string studentName = "Hannah Wilkinson";
        int dollars;
        double quarters;
        double dimes;
        double nickles;
        double pennies;
        double total;
        double coins;

        //display studentName and purpose
        Console.WriteLine("Student Name: " + studentName);
        Console.WriteLine("This application calculates the value of the change you enter\n");

        //calculate dollars and print
        Console.Write("Please enter the number of dollar bills: ");
        dollars = int.Parse(Console.ReadLine());
        //dollars = dollars / 100;

        //calculate quarters and print
        Console.Write("Please enter the number of quarters: ");
        quarters = int.Parse(Console.ReadLine());
        quarters = (quarters * 0.25);

        //calculate dimes and print
        Console.Write("Please enter the number of dimes: ");
        dimes = int.Parse(Console.ReadLine());
        dimes = (dimes * 0.10);

        //calculate nickles and print
        Console.Write("Please enter the number of nickles: ");
        nickles = int.Parse(Console.ReadLine());
        nickles = (nickles * 0.05);

        //calculate pennies and print
        Console.Write("Please enter the number of pennies: ");
        pennies = int.Parse(Console.ReadLine());
        pennies = (pennies * 0.01);

        //calculate the coin amount
        coins = quarters + dimes + nickles + pennies;
        Console.WriteLine($"\nYour total change entered is {dollars} dollar bills and {coins:c} cents");

        //calculate the total
        total = (double)dollars + coins;
        Console.WriteLine($"\nThe amount of U.S. currency entered is: {total:c}");

        //calculate and display the conversion amount
        double conversion = total * 0.73;
        Console.WriteLine($"The conversion equals {conversion:c}");
    }
}
