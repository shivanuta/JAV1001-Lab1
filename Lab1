/*Name:Kavya Chapparapu
 Student id:A00246626
 Name :Shiva Rama Krishna Nutakki
Student id:A00245380
Program Description: This program is about different  units of conversions .
                     It is according to the user's choice
                     It's termination also according to the user's decision.*/


import java.io.*;
import java.util.Scanner;
class Conversion
{
  public static void km_mi(double km)//method which conerts kilometers to miles
  {
    System.out.println(km +"km is equal to "+(km*0.62)+"miles");
  }
  public static void mi_km(double mi)//method which converts miles to kilometers
  {
    System.out.println(mi+"miles is equal to "+(mi*1.61)+"Km");
  }
  public static void cm_in(double cm)//method which converts centimeters to inches
  {
    System.out.println(cm+"cm is equal to "+(cm*0.39)+"inches");
  }
  public static void in_cm(double in)//method which converts inches to centimeters
  {
    System.out.println(in+"inches is equal to "+(in*2.54)+"cm");
  }
  public static void kg_lb(double kg)//method which converts kilograms to pounds
  {
    System.out.println(kg+"kgs is equal to "+(kg*2.2)+"lbs");
  }
  public static void lb_kg(double lb)//method which converts pounds to kilograms
  {
    System.out.println(lb+"lbs is equal to "+(lb*0.45)+"kgs");
  }
  public static void main(String args[])
  {
    Scanner scan = new Scanner(System.in);
    int no=1;
    do
     {
       if (no==2)// if user doesnt want to continue
          break;
    System.out.println("\t1:Kilometers to Miles\n\t2:Miles to Kilometers");//  Displaying the different conversion options
    System.out.println("\t3:Centimeters to Inches\n\t4:Inches to Centimeters");
    System.out.println("\t5:Kilograms to Pounds\n\t6:Pounds to Kilograms");
    System.out.print("\tEnter the numeric value of corresponding choice of conversion:");//asking the user for their choice
    int  choice=scan.nextInt();// reading  input from the user
  if(no == 1)
  {
  switch(choice)
  {
      case 1:
              System.out.print("Enter  no of Kilometers to be converted:");//case of kilometers to miles conversion
              double km = scan.nextDouble();
              km_mi(km);
              break;
      case 2:
             System.out.print("Enter no of Miles to be converted:");//case of miles to kilmeters conversion
             double mi = scan.nextDouble();
             mi_km(mi);
             break;
      case 3:
              System.out.print("Enter no of Centimetes to be converted:");//case of centimeters to inches conversion
              double cm = scan.nextDouble();
              cm_in(cm);
              break;
       case 4:
              System.out.print("Enter no of Inches to be converted:");//case of inces to centimeters converwsion
              double in = scan.nextDouble();
              in_cm(in);
              break;
       case 5:
              System.out.print("Enter kilograms to be converted:");//case of kilograms to pounds cpnversion]
              double kg = scan.nextDouble();
              kg_lb(kg);
              break;
       case 6:
              System.out.print("Enter no of pounds to be converted:");//case of pounds to kilograms conversion
              double lb = scan.nextDouble();
              lb_kg(lb);
              break;
        default:
                System.out.println("Wrong choice \n Try again!");//default case
    }
  }

    System.out.print("Press 1:YES \t 2:NO\nDo you want continue :");//asking user's choice whether he/she wants to continue for other conversions
    no =scan.nextInt();
  }
  while(true);
}
}
