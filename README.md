# hi-lo_game

In this game, there is a given range of numbers. The player (human) chooses a specific number within that range. The computer's objective is to guess the chosen number by utilizing a binary search algorithm.

The binary search algorithm works as follows:

1. The computer identifies the midpoint of the given range.
2. It checks if the chosen number is equal to the midpoint. If yes, the game ends, and the computer has successfully guessed the number.
3. If the chosen number is greater than the midpoint, the computer narrows down its search to the upper half of the range and repeats step 1.
4. If the chosen number is less than the midpoint, the computer narrows down its search to the lower half of the range and repeats step 1.
5. This process continues until the computer successfully guesses the chosen number.


The game concludes when the computer accurately guesses the player's chosen number, and the number of attempts taken by the computer is recorded. The objective is to find the chosen number in the fewest possible attempts using the binary search algorithm.
