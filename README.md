import java.util.Calendar;
import java.util.Scanner;

/********
 *
 *   File: BMI_Master_KrushitMoradiya-Assignment-04
 *   By: Krushit Moradiya
 *   Date: 03-16-2023
 *
 *   Description: In this program we have make a master version of BMI caluculator, we have to put for loop in
 *                the switch statment  and we also have create a method in main method for this program.
 *
 *  ********/
public class KrushitMoradiya {
    public static void main(String[] args) {
        bmistatus();
    }

    public static void bmistatus() {

        boolean check =true;
        Scanner input = new Scanner(System.in);
        String option = "";
        while (!option.equals("!"))

            do {  private static void welcomemessage(){

                System.out.println("My CSC 210 Projects:");
                System.out.println("   1. BMI ,English, Standard Version");
                System.out.println("   2. BMI ,Metric, Standard Version");
                System.out.println("   3. BMI ,English, Professional Version");
                System.out.println("   4. BMI ,Metric, Professional Version");
                System.out.println("\n[ USER MANUAL ] Enter an exlamation mark ! to end.");
                System.out.print("Please enter the version you want to try: ");}

                option = input.nextLine().trim();



                switch (option) {

                    case "English Standard":
                        private static void englishstandard() {
                        System.out.println("English Standard");
                        System.out.println("-".repeat(90));
                        System.out.println("--Welcome to:");
                        System.out.println("--           BODY MASS INDEX (BMI) Computation, English version:");
                        System.out.println("--                                                             by Krushit Moradiya");
                        System.out.println("-".repeat(90));

                        Scanner a = new Scanner(System.in);
                        System.out.print("Please enter your full Name:");
                        String v = input.nextLine();
                        System.out.print("Please enter height in feet and inches For " + ": ");
                        int feet = input.nextInt();
                        int inches = input.nextInt();
                        System.out.print("Please enter weight for " + v + ": ");
                        double weight = input.nextDouble();
                        System.out.printf("-- Summary Report for %2S", v);
                        //System.out.printf(" %2S" , a);
                    }

                        double height = (feet * 12) + inches;


                        double BMI;
                        BMI = (weight) / (height * height) * 703;
                        System.out.print("\n-- BMI:  \t\t\t" + BMI);
                        System.out.printf(" (or %.1f if rounded) ", BMI);


                        double i;
                        i = BMI;

                        System.out.print("\n");
                        System.out.print("--Weight Status: \t");


                        if (i < 18.5) {
                            System.out.print("Underweight!!");
                            System.out.println(" ");
                        } else if (i <= 25) {
                            System.out.print("Healthyweight!!");
                            System.out.println(" ");

                        } else if (i <= 30) {

                            System.out.print("Overweight!!");
                            System.out.println(" ");

                        } else {
                            System.out.println("Obesity");

                        }


                        System.out.println(" ");
                        System.out.println("The SFSU Mashouf Wellness Center at 755 Font Blvd.");
                        System.out.println(" ");
                        System.out.println("-".repeat(90));
                        System.out.println("--Thank you for using my program," + "!");
                        System.out.println("-".repeat(90));


                        break;
                    case "Metric Standard":

                        System.out.println("Metric Standard");
                        System.out.println("-".repeat(90));
                        System.out.println("--Welcome to:");
                        System.out.println("--           BODY MASS INDEX (BMI) Computation, Metric version:");
                        System.out.println("--                                                             by Krushit Moradiya");
                        System.out.println("-".repeat(90));
                        Scanner c = new Scanner(System.in);
                        System.out.print("Please enter your full Name:");
                        String n = c.nextLine();
                        System.out.print("Please enter height in centimetres for " + n + ": ");
                        double centi = c.nextDouble();
                        System.out.print("Please enter weight in pounds for in Kilograms for " + n + ": ");
                        double d = c.nextDouble();
                        System.out.print("-- Summary Report for\t");
                        System.out.printf("%2S ", n);


                        double h = centi;


                        double bmi;
                        bmi = (d) / (h * h) * 10000;
                        System.out.println();
                        System.out.printf("-- BMI:\t\t\t" + bmi);
                        System.out.printf(" (or %.1f if rounded) ", bmi);


                        double b;
                        b = bmi;

                        System.out.print("\n");
                        System.out.print("--Weight Status: \t");


                        if (b < 18.5) {
                            System.out.print("Underweight!!");
                            System.out.println(" ");
                        } else if (b <= 25) {
                            System.out.print("Healthyweight!!");
                            System.out.println(" ");

                        } else if (b <= 29.5) {

                            System.out.print("Overweight!!");
                            System.out.println(" ");

                        } else {
                            System.out.println("Obesity");

                        }


                        System.out.println(" ");
                        System.out.println("The SFSU Mashouf Wellness Center at 755 Font Blvd.");
                        System.out.println(" ");
                        System.out.println("-".repeat(90));
                        System.out.println("--Thank you for using my program," + n + "!");
                        System.out.println("-".repeat(90));


                        break;
                    case "English Professional":
                        System.out.println("English Professional");
                        System.out.println("-".repeat(90));
                        System.out.println("--Welcome to:");
                        System.out.println("--              BODY MASS INDEX (BMI) Computation, ENGLISH version PRO,");
                        System.out.println("--                                                                    by Krushit Moradiya");
                        System.out.println("-".repeat(90));
                        Scanner f = new Scanner(System.in);
                        System.out.print("Please Enter Your Name:");
                        String name = f.nextLine();
                        System.out.print("Please enter your height in Feet and inches for " + name + " : ");
                        int fet = f.nextInt();
                        int inc = f.nextInt();
                        System.out.print("Please Enter your weight in pounds for " + name + " : ");
                        double wt = input.nextDouble();
                        System.out.printf("--Summary Report for %2S", name);
                        System.out.print("\n--Date and Time :");

                        Calendar cal = Calendar.getInstance();
                        System.out.format(" %tB %te, %tY at ", cal, cal, cal);
                        System.out.format(" %tl:%tM:%tS %tp ", cal, cal, cal, cal);

                        String s = null;

                        double ht = (fet * 12) + inc;

                        double EngBMI;
                        EngBMI = (wt) / (ht * ht) * 703;
                        System.out.printf("\n-- BMI: \t\t\t " + EngBMI);
                        System.out.printf("(or %.1f if rounded)", EngBMI);


                        System.out.print("\n");
                        System.out.print("--Weight Status: \t");

                        if (EngBMI < 18.5) {
                            s = "Underweight";
                            System.out.print("Underweight");
                            System.out.println(" ");
                        } else if (EngBMI <= 25) {
                            s = "Healthyweight";
                            System.out.print("Healthyweight");
                            System.out.println(" ");
                        } else if (EngBMI <= 30) {
                            s = "Overweight";
                            System.out.print("Overweight");
                            System.out.println(" ");
                        } else {
                            s = "Obesity";
                            System.out.print("Obesity");
                        }
                        System.out.println(" ");

                        System.out.println(" ");
                        System.out.printf("Please enter the LOW weight in pounds  for : ", name);
                        double low = input.nextDouble();
                        System.out.printf("Please enter the HIGH weight in pounds  for : ", name);
                        double high = input.nextDouble();

                        System.out.println("-".repeat(55));
                        System.out.println("| WEIGHT\t\t\t|\t BMI\t|\tWEIGHT STATUS\t | ");
                        System.out.println("-".repeat(55));

                        final String ANSI_YELLOW_BACKGROUND = "\u001B[43m";
                        final String ANSI_BLACK = "\u001B[30m";
                        final String ANSI_RESET = "\u001B[0m";

                        double j;
                        for (j = low; j <= high; j += 5.50) {
                            System.out.print("| " + j + "\t\t");
                            double ebmi = (j / (ht * ht)) * 703;

                            System.out.print("\t\t| ");


                            if (ebmi < 18.5) {
                                System.out.printf("%.2f \t| ", ebmi);
                                System.out.print("Underweight \t");


                                if (j == low) {
                                    // System.out.print("Low");
                                    System.out.printf(ANSI_YELLOW_BACKGROUND + ANSI_BLACK + "(LOW)" + ANSI_RESET + "|");

                                }
                                System.out.print("     |");
                            } else if (ebmi < 25) {
                                System.out.printf("%.3f \t| ", ebmi);
                                System.out.print("HealthyWeight\t\t |");
                            } else if (ebmi < 30) {
                                System.out.printf("%.4f \t| ", ebmi);
                                System.out.print("Overweight\t\t |");

                            } else {
                                System.out.printf("%.5f \t| ", ebmi);
                                System.out.print("Obesity\t\t\t |");
                            }
                            BMI = (wt) / (ht * ht) * 703;


                            if (j + 5.5 > wt && j < wt) {
                                System.out.printf("\n| %.2f  \t\t", wt);
                                System.out.printf("\t| %.5f", BMI);
                                System.out.print("\t| " + s);
                                System.out.print("(this)\t\t |");
                            }

                            System.out.println(" ");
                        }


                        double g = (high / (ht * ht)) * 703;
                        System.out.print("| " + high + "\t\t\t| " + (float) j + "\t\t| Obesity\t");
                        System.out.print(ANSI_YELLOW_BACKGROUND + ANSI_BLACK + "(HIGH)" + ANSI_RESET + " \t |");
                        System.out.println(" ");
                        System.out.println("The SFSU Mashouf Wellness Center at 755 Font Blvd");
                        System.out.println(" ");
                        System.out.println("-".repeat(90));
                        System.out.println("--Thank you for using my program ," + name + "!");
                        System.out.println("-".repeat(90));
                        break;

                    case "Metric Professional":
                        System.out.println("Metric Professional");
                        System.out.println("-".repeat(90));
                        System.out.println("--Welcome to:");
                        System.out.println("--              BODY MASS INDEX (BMI) Computation, Metric version PRO,");
                        System.out.println("--                                                                 by Krushit Moradiya");
                        System.out.println("-".repeat(90));
                        Scanner t = new Scanner(System.in);
                        System.out.print("Please Enter Your Name:");
                        String nme = t.nextLine();
                        System.out.print("Please enter your height in centimeters for " + nme + " : ");
                        int cnti = t.nextInt();

                        System.out.print("Please Enter your weight in Kilogram for " + nme + " : ");
                        double wght = t.nextDouble();
                        System.out.printf("--Summary Report for %2S", nme);
                        System.out.print("\n--Date and Time:");

                        Calendar caln = Calendar.getInstance();
                        System.out.format(" %tB %te, %tY at ", caln, caln, caln);
                        System.out.format(" %tl:%tM:%tS %tp ", caln, caln, caln, caln);

                        String o = null;


                        double BMIsts;
                        BMIsts = (wght) / (cnti * cnti) * 10000;
                        System.out.printf("\n-- BMI: \t\t " + BMIsts);
                        System.out.printf("(or %.1f if rounded)", BMIsts);


                        System.out.print("\n");
                        System.out.print("--Weight Status: ");

                        if (BMIsts < 18.5) {
                            o = "Underweight";
                            System.out.print("Underweight");
                            System.out.println(" ");
                        } else if (BMIsts <= 25) {
                            o = "Healthyweight";
                            System.out.print("Healthyweight");
                            System.out.println(" ");
                        } else if (BMIsts <= 30) {
                            o = "Overweight";
                            System.out.print("Overweight");
                            System.out.println(" ");
                        } else {
                            o = "Obesity";
                            System.out.print("Obesity");
                        }
                        System.out.println(" ");

                        System.out.println(" ");
                        System.out.printf("Please enter the LOW weight in kilograms  for : ", nme);
                        double Low = input.nextDouble();
                        System.out.printf("Please enter the HIGH weight in kilograms  for : ", nme);
                        double High = input.nextDouble();

                        System.out.println("-".repeat(55));
                        System.out.println("| WEIGHT\t\t\t|\t BMI\t|\tWEIGHT STATUS\t | ");
                        System.out.println("-".repeat(55));

                        final String ANSI_YELLOW_BKGD = "\u001B[43m";
                        final String ANSI_BLK = "\u001B[30m";
                        final String ANSI_RST = "\u001B[0m";

                        double k;
                        for (k = Low; k <= High; k += 2.50) {
                            double Bmi = (k / (cnti * cnti)) * 10000;
//            System.out.printf("\t|%.2f", bmi);

                            //System.out.print("\t\t| ");


                            if (Bmi < 18.5) {
//          System.out.printf(" %.2f" , i);
                                System.out.printf("|  %.2f \t\t", k);
                                System.out.print("\t| ");
                                System.out.printf("%.2f \t| ", Bmi);
                                System.out.print("Underweight \t");


                                if (k == Low) {
                                    // System.out.print("Low");
                                    System.out.printf(ANSI_YELLOW_BKGD + ANSI_BLK + "(LOW)" + ANSI_RST + "|");

                                }
                                System.out.print("     |");
                            } else if (Bmi < 25) {
//                System.out.printf("%.2f" , i);
                                System.out.printf("|  %.3f \t\t", k);
                                System.out.print("\t| ");
                                System.out.printf("%.3f \t| ", Bmi);
                                System.out.print("HealthyWeight\t\t |");
                            } else if (Bmi < 30) {
                                //  System.out.printf(" %.2f" , i);
                                System.out.printf("|  %.4f \t\t", k);
                                System.out.print("| ");
                                System.out.printf("%.4f \t| ", Bmi);
                                System.out.print("Overweight\t\t |");

                            } else {
                                System.out.printf("| %.5f \t\t", k);
                                System.out.print("| ");
                                System.out.printf("%.5f  | ", Bmi);
                                System.out.print("Obesity\t\t\t |");


                            }
                            BMI = (wght) / (cnti * cnti) * 10000;


                            if (k + 2.5 > wght && k < wght) {
                                System.out.printf("\n|  %.3f  \t", wght);
                                System.out.printf("    | %.3f", BMI);
                                System.out.print("    | " + o);
                                //  System.out.print("\t");
                                System.out.print("(this)\t |");
                            }

                            System.out.println(" ");
                        }


                        double p = (High / (cnti * cnti)) * 10000;
                        System.out.print("| " + High + "\t\t\t| " + (float) p + "\t| Obesity\t");
                        System.out.print(ANSI_YELLOW_BKGD + ANSI_BLK + "(HIGH)" + ANSI_RST + " \t |");
                        System.out.println(" ");
                        System.out.println("The SFSU Mashouf Wellness Center at 755 Font Blvd");
                        System.out.println(" ");
                        System.out.println("-".repeat(90));
                        System.out.println("--Thank you for using my program ," + nme + "!");
                        System.out.println("-".repeat(90));
                        break;
                    default:
                        System.out.println("\n Thank you for trying my programs!");
                }

            } while (check != true);






    }
}
