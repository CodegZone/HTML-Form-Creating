# Java-Converter
Advanced Application Assignment

import java.util.*;
 
class Fahrenhei_To_Celsius {
  public static void main(String[] args) {
    float temp;
    Scanner in = new Scanner(System.in);
 
    System.out.println("Enter temperature in Fahrenheit");
    temp = in.nextInt();
 
    temp = ((temp - 32)*5)/9;
 
    System.out.println("temperature in Celsius = " + temp);
  }
}
