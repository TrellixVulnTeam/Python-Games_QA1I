# Python-Games

01. Guessing Game Challenge

Program that picks a random integer from 1 to 100, and has players guess the number.

  The rules are:
	1. If a player's guess is less than 1 or greater than 100, say "OUT OF BOUNDS"
	2. On a player's first turn, if their guess is:
    2.1. within 10 of the number, return "WARM!"
    2.1. further than 10 away from the number, return "COLD!"
  3. On all subsequent turns, if a guess is:
    3.1. closer to the number than the previous guess return "WARMER!"
    3.2. farther from the number than the previous guess, return "COLDER!"
  4. When the player's guess equals the number, tell them they've guessed correctly and how many guesses it took!
