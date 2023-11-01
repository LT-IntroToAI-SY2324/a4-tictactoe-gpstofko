# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe?
    Writing the has_won function was the hardest part because figuring out all the win conditions and how to efficently check if the player has won with the least amount of code was hard. Not only that but I took my own approach to writing the code so it may have not worked with all the asserts.
2. Explain how you would add a computer player to the game.
    I would add a function that would recognize patterns and see possible win scenarios to play. You could also just make the computer play a random move on a random open square too.
3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it.
    I would look for pairs of two in a row made by the same player and then either see if it matches my own player to win the game or if its the opposite player to prevent them from winning. If there are no two in a row players on the board then the computer would just randomly play a move anywhere.