Simple JavaScript game called "Guess My Number". The goal is to guess the secret number in as few attempts as possible. The game has the following features:

- the program generates a secret number between 1 and 20
- the player has 20 attempts to guess the secret number
- the number of remaining turns is tracked in the Score field
- the program tracks the best score (fewest number of turns taken to guess the secret number) in the Highscore field until the browser is refreshed
- the player enters a guess number into the guess box and clicks Check!
- the program tells the player if the guess number is lower or higher than the secret number
- the program also tells the player if the guess is out-of-bounds (i.e. less than 1 or greater than 20)
- the player continues to enter a guess until either the secretNumber is correctly guessed or the user is out of turns
- each unsuccessful guess attempt is subtracted from the score field
- if the player successfully guesses the correct answer before running out of turns the screen background turns green, the secret number is displayed, and the program text indicates that secret number was successfully guessed
- if the player does not guess the correct answer before running out of turns the screen background turns red, the secret number is displayed, and the program text indicates that secret number was not successfully guessed
- the program tracks best score in the Highscore field until the browser is refreshed
- upon guessing the secret number, if the Score from the current game is higher than the Highscore value, then the current Score value replaces the Highscore value
- the player can click the Again! button to play another game
