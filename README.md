Project Overview: Guessing Game

The Guessing Game project is a simple, interactive game implemented in Python. The primary objective of the game is to guess a randomly selected secret number within a user-defined range. The player is provided with feedback on whether their guesses are too high or too low, and they have a limited number of attempts to guess the correct number.

Key Features

Random Secret Number Generation: The game generates a secret number within a range specified by the player (between 1 and 100).

Limited Attempts: Players have up to 5 attempts to guess the secret number.

Feedback Mechanism: The game provides feedback on each guess, indicating whether the guess is too high or too low.

Replay Option: After each game, players have the option to play again or exit the game.

How to Play

Start the Game: Run the Python script to start the game.

Set Range: Enter the maximum number you want to guess (between 1 and 100).

Make Guesses: Enter your guesses one by one. The game will inform you if your guess is too high or too low.

Win or Lose: The game ends when you guess the correct number or run out of attempts. You can then choose to play again or exit.

Class and Methods

GuessingGame Class

Attributes:

secret_number: The number the player needs to guess.

max_guesses: The maximum number of guesses allowed (default is 5).

guesses: A list to store the player's guesses.

Methods:

__init__(): Initializes the game with default settings.

set_secret_number(max_num): Sets the secret number to a random value within the specified range.

get_max_guesses(): Returns the maximum number of guesses allowed.

get_guesses(): Returns the list of guesses made by the player.

add_guess(guess): Adds a guess to the list of guesses.

get_last_guess(): Returns the last guess made by the player.

is_guess_correct(guess): Checks if the guess is correct.

is_game_over(): Checks if the game is over due to correct guess or exceeding the number of allowed guesses.

play_game(): Contains the main game loop where the player makes guesses and receives feedback.

display_menu(): Displays the game menu for replay or exit options.

run(): Runs the game, allowing the player to play or exit based on menu choices.
