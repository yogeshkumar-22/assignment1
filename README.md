//Write a java program that reads a Celsius degree in a double value from the console then converts it to Fahrenheit 
//and displays the result. The formula for the conversion is as follows: 
//Fahrenheit = (9 / 5) * Celsius + 32 
//Hint: In Java, 9 / 5 is 1, but 9.0 / 5 is 1.8. 
//Here is a sample run: 
//Enter a degree in Celsius: 43 
//43 Celsius is 109.4 Fahrenheit

import java.util.Scanner;
public class Q1 {
public static void main(String[] args) {
Scanner input = new Scanner(System.in);
System.out.print("Enter a degree in Celsius: ");
double celsius = input.nextDouble();
double fahrenheit = (9.0 / 5) * celsius + 32;
System.out.println(celsius + " Celsius is " + fahrenheit + " Fahrenheit");
input.close();
}
}
