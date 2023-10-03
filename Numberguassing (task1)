import java.util.*;

public class numbergussing {
    public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        String play = "yes";

        //while loop to determine if we are going to play the game again
        while(play.equals("yes")){
            Random rand = new Random();
            int randNum = rand.nextInt(100);
            int guess = -1;
            int tries = 0;

            //while loop to check if the game is over 
            while(guess != randNum)
            {
                System.out.println("Guess a number between 1 and 100: ");
                guess = reader.nextInt();
                tries++;

                if(guess == randNum)
                {
                    System.out.println("Great! you guessed the number!");
                    System.out.println("it only took you "+tries+" guesses!");
                    System.out.println("would you like to play again? Yes or No: ");
                    play = reader.next().toLowerCase();

                }
                else if(guess > randNum){
                    System.out.println("Your guess is too high, try again.");
                }
                else{
                    System.out.println("your guess is too low, try again.");
                }
            }
        }
        reader.close();
    }    
}
