# COP1220-6-Module-1-Programming-Exercise
This is a repository link of the COP1220-6 Module 1 Programming Exercise

// This exercise program is created to convert inches to centimeters.
using System;
// This is the class name.
class Program
{
  // This is the main method.
  static void Main()
  {
    // This is the variable declaration.
    Console.WriteLine("Enter the number of inches:");
    // This is the variable declaration.
    double inches = Convert.ToDouble(Console.ReadLine());
    // This is the second variable declaration.
    double centimeters = inches * 2.54;
    // This is the output statement.
    Console.WriteLine("{0} inches is {1} centimeters", inches, centimeters);
  }
}
