# Tic-Tac-Toe-Game

Here's a basic tutorial of building a Tic-Tac-Toe game using Python. 

Let's first understand the project scope: 
- We need to print a board.
- Take in player input.
- Place their input on the board.
- Check if the game is won,tied, lost, or ongoing.
- Repeat third and fourth point until the game has been won or tied.
- Ask if players want to play again.

## Some Hints for you to follow: 
- Let's start by deciding how to store where players put their Xs and Os. Think of it like a keypad where each number corresponds to a spot on the 3 by 3 board.

- Create a list called "board" to keep track of player moves, matching the board's size.

- Now, let's make a function that prints a real game board, not just the list. We want it to look like an actual game board when we play.

- Write a function that takes an 'X' or 'O' and a number, and then stores it in our list.

- We'll use input() to get the player's move. Give it a try to make sure you get how it works.

- Next, create a function that checks if someone has won or if the game is a tie. Think of it like looking for a pattern in a row or column.

- Also, check for a tie when the board is full, meaning no one has won.

- Now, let's get into the game. Write functions that do different parts of the game, like asking for a move, updating the board, checking for a win, and showing the board.

- To keep the game going, use a while loop. It'll keep running as long as the board isn't full and no one has won.

- Think of using boolean values like flags to show what's happening in the game. Let's make it feel like a real, ongoing game!
