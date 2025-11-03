# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?

Although not terribly difficult, checking if a player has won was the most difficult part, requiring the array of winning combos, and then having to iterate through them after each move to check if a player has pieces in all 3 spots listed in each combo.

2. Explain how you would add a computer player to the game.

After the player goes (or before, if you want them to be X), a function would be called, where the program would decide its optimal move. You would need to value certain moves and also assign a value to blocking the real player, so the computer could iterate through each spot and determine which placement would yield the most value.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.

You would need to value certain moves and also assign a value to blocking the real player, so the computer could iterate through each spot and determine which placement would yield the most value. For example, it would determine that a spot that contributes towards 3 winning combos (a corner) and also blocks the player from their in-progress combos (as in already having some spaces filled out contributing towards it) would be worth more than a spot that only works towards 2 winning combos and doesn't block an in-progress combo being worked towards by the player.
