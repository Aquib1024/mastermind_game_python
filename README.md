# mastermind_game_python

This is a Python implementation of the classic board game "Mastermind." In this game, you have a limited number of attempts to guess a secret color code. The code consists of a sequence of colors, and you must guess both the colors and their correct positions.
<br>
<h2>How to Play</h2>
<br>
1. You have a limited number of tries (defined by TRIES) to guess the secret color code.
<br>
2. The valid colors are represented by the following single-letter codes: ["R" (Red), "G" (Green), "B" (Blue), "Y" (Yellow), "W" (White), "O" (Orange)].
<br>
3. Enter your guesses as a sequence of these single-letter codes, separated by spaces.
<br>
4. The program will provide feedback after each guess:
<br>
  -> The number of correctly guessed colors in the correct positions (Correct Positions).
<br>
  -> The number of correctly guessed colors in the wrong positions (Incorrect Positions).
<br>
5. Keep guessing until you correctly guess the entire code or run out of attempts.
<br>
<h2>Code Features</h2>
<br>
1. Generates a random secret color code for each game.
<br>
2. Validates user input for guess format and color correctness.
<br>
3. Tracks and displays the number of correct and incorrect positions for each guess.
<br>
4. Provides feedback on the number of tries it took to guess the code.
<br>
<h2>Configuration</h2>
<br>
You can customize the game by adjusting the following constants in the code:
<br>
  COLORS: Define the valid colors for the game.
<br>  
  TRIES: Set the number of attempts the player has to guess the code.
<br>  
  CODE_LENGTH: Define the length of the secret color code.
<br>
<h2>Acknowledgments</h2>
<br>
1. Inspired by the classic board game "Mastermind."
<br>
2. Built with Python's random module and user input validation.
