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
