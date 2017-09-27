# W3Ex01
How to start a javascript to run
------------------
public class W3E5 {
    public void run() {
        System.out.println("Sup");
    }

    public static void main(String[] args) {
        new W3E5().run();

    }
}

-------------------
How to use the 'if' statement (about alcohol)

import java.util.Scanner;

public class W3E4 {
    public void run() {
        Scanner alcoholInfo = new Scanner(System.in);
        int age = alcoholInfo.nextInt();
        if (age < 18) {
            System.out.println("You are NOT allowed to buy alcohol!");
        } else {
                System.out.println("You are allowed to buy alcohol");
            }
        }




    public static void main(String[] args) {
        new W3E4().run();
    }
}
------------------
Roman numbers code:

import java.util.Scanner;

/**
 * Created by 452318 on 25/09/17.
 */
public class W305 {
    public void run() {
        Scanner inputScanner = new Scanner(System.in);
        System.out.println("insert a number from 1 to 10");
        int number = inputScanner.nextInt();
        if (number < 0 && number > 10) ;
        System.out.println("This is the Roman Numbers");
        if (number == 1) {
            System.out.println("I");
        } else if (number == 2) {
            System.out.println("II");
        } else if (number == 3) {
            System.out.println("III");
        } else if (number == 4) {
            System.out.println("IV");
        } else if (number == 5) {
            System.out.println("V");
        } else if (number == 6) {
            System.out.println("VI");
        } else if (number == 7) {
            System.out.println("VII");
        } else if (number == 8) {
            System.out.println("VIII");
        } else if (number == 9) {
            System.out.println("IX");
        } else if (number == 10) {
            System.out.println("X");

        }
    }

    public static void main(String[] args) {
        new W305().run();

    }
}
-----------------------------------


--------------------------------

mport java.util.Scanner;

public class W3Ex06 {
    public void run() {
        Scanner inputScanner = new Scanner(System.in);
        System.out.println("Put your first number in");
        int number1 = inputScanner.nextInt();
        System.out.println("Put your second number in");
        int number2 = inputScanner.nextInt();

        int outcome = number1 + number2;
        int outcome1 = number1 - number2;
        int outcome2 = number2 - number1;
        int outcome3 = number1 * number2;
        int outcome4 = number1 / number2;
        int outcome5 = number2 / number1;
        int outcome6 = number1 % number2;
        int outcome7 = number2 % number1;

        System.out.println(outcome);
        System.out.println(outcome1);
        System.out.println(outcome2);
        System.out.println(outcome3);
        System.out.println(outcome4);
        System.out.println(outcome5);
        System.out.println(outcome6);
        System.out.println(outcome7);




    }

    public static void main(String[] args) {
        new W3Ex06().run();
    }
}

---------------
/**
 * Created by 452318 on 26/09/17.
 */
public class W307 {
    public void run() {
        Scanner inputScanner = new Scanner(System.in);

        System.out.println("Enter your height (in meters): ");
        double height = inputScanner.nextDouble();
        height = height * height;

        System.out.println("Enter your weight (in KG): ");
        int weight = inputScanner.nextInt();

        double BMI = weight / height;

        System.out.println("Your BMI is: " + BMI);
        if (BMI < 18.5) {
            System.out.println("Underweight");
        }

        if (BMI >=18.5 && BMI <25) {
            System.out.println("Normal weight");
        }
        if (BMI >=25 && BMI < 30) {
            System.out.println("Overweight");
        }
        if (BMI >30) {
            System.out.println("Obesity");
        }


    }

    public static void main(String[] args) {
        new W307().run();
    }
}


------------------------
import java.util.Scanner;

/**
 * Created by 452318 on 26/09/17.
 */
public class W308 {
    public void run() {
        Scanner inputScanner = new Scanner(System.in);

        System.out.println("Input first value");
        int number = inputScanner.nextInt();

        System.out.println("Input second value");
        int number1 = inputScanner.nextInt();

        System.out.println("Input value: " + number);
        System.out.println("Input value: " + number1);
        if (number > number1) {
            System.out.println("The largest value is: " + number + ".");

        }

        if (number1 > number) {
            System.out.println("The largest value is: " + number1 + ".");
        }

        else {
            System.out.println("the value are equal.");

        }


    }

    public static void main(String[] args) {
        new W308().run();
    }
}
--------------------

import java.util.Scanner;

/**
 * Created by 452318 on 26/09/17.
 */
public class W3EX09 {
    public void run() {
        Scanner inputScanner = new Scanner (System.in);
        System.out.println("Put in a value between 1 and 5000");
        int value = inputScanner.nextInt();

        value = value * 1000000;
        System.out.println("The multiplied number will be: " + value);




    }

    public static void main(String[] args) {
        new W3EX09().run();
    }

}
-----
import java.util.Random;

public class W3Ex13 {
    public void run () {

        Random bounds = new Random();

        int Lowerbound;

        for ( int x = 0 ; x < 100 ;x ++ ) {
            Lowerbound = bounds.nextInt(6) + 1;

            System.out.println(Lowerbound);

        }



    }

    public static void main(String[] args) {
        new W3Ex13().run();
    }
}
