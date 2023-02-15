# Leap-Year-Calculator

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int year, zodiac;
        Scanner scanner = new Scanner(System.in);

        System.out.println("Yıl giriniz: ");
        year = scanner.nextInt();

        if(year % 4 == 0 && year % 100 != 0){
            System.out.println(year + " bir artık yıldır.");
        }
        else if(year % 100 == 0 && year % 400 == 0){
            System.out.println(year + " bir artık yıl değildir.");
        }
        else{
            System.out.println(year + " bir artık yıl değildir.");
        }

    }
}
