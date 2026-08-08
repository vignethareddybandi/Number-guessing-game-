import java.util.Scanner;

public class NumberGuessing {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int number = 7;

        System.out.print("Guess the number between 1 and 10: ");
        int guess = sc.nextInt();

        if (guess == number)
            System.out.println("Correct! You guessed the number.");
        else if (guess < number)
            System.out.println("Too low!");
        else
            System.out.println("Too high!");

        sc.close();
    }
}