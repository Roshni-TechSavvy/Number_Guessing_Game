# Number_Guessing_Game

1.Difficulty Levels: The player first chooses Easy, Medium, or Hard. Each level has a different number range and number of attempts:
Easy: 1–50, 10 attempts
Medium: 1–100, 7 attempts
Hard: 1–200, 6 attempts
2.Random Number: Python's random.randint() generates a secret random number within the selected range.
3.User Guess: The player enters a number. The program checks whether the input is a valid whole number and whether it is within the required range.
4.Hints: If the guess is smaller than the secret number, it displays "Higher!". If the guess is greater, it displays "Lower!".
5.Win or Lose: If the player guesses correctly within the available attempts, they win. Otherwise, the program reveals the secret number after all attempts are used.
6.Score Tracking: The program keeps track of the number of wins and rounds played.
7.Play Again: After each round, the player can choose y to play again or n to exit.
Functions used
choose_difficulty() → selects the difficulty level.
get_guess() → takes and validates the player's guess.
play_round() → controls one complete round of the game.
main() → controls the overall game, score, and replay option.
random.randint() → generates the secret number.

Overall, this project demonstrates functions, dictionaries, loops, conditions, input validation, random number generation, and score tracking in Python.
