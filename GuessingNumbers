package pl.michalgorecki;

import java.util.Random;
import java.util.Scanner;

public class apka1 {

    public static void main(String[] args) {
        Random random = new Random();
        int numberToGuess = random.nextInt(100) + 1;
        Scanner scanner = new Scanner(System.in);
        boolean wasNumberGuessed = false;

        while (!wasNumberGuessed) {
            System.out.println("Podaj liczbę: ");
            int userNumber = scanner.nextInt();

            if (userNumber < numberToGuess) System.out.println("Your number is too small");
            else if (userNumber > numberToGuess) System.out.println("Your number is too high");
            else {
                System.out.println("Correct answer");
                wasNumberGuessed = true;
            }
        }
    }
