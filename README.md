# Tic_Tac_Toe
This is a small demonstration of a game developed in Python utilizing the 'pygame' library

### What is Tic Tac Toe?
Tic Tac Toe is one of the most played games and is the best time killer game that you can play anywhere with just a pen and paper. If you don’t know how to play this game don’t worry let us first understand that.

The game is played by two individuals. First, we draw a board with a 3×3 square grid. The first player chooses ‘X’ and draws it on any of the square grid, then it’s the chance of the second player to draw ‘O’ on the available spaces. Like this, the players draw ‘X’ and ‘O’ alternatively on the empty spaces until a player succeeds in drawing 3 consecutive marks either in the horizontal, vertical or diagonal way. Then the player wins the game otherwise the game draws when all spots are filled.

![Game Image](https://github.com/alinauman/Tic_Tac_Toe/blob/main/Game_Result.PNG)

### Project Details
This project is built using the Python library, [pygame](https://www.pygame.org/news). It will allow us to create the window and draw images and shapes on the window. This way we will capture mouse coordinates and identify the block where we need to mark ‘X’ or ‘O’. Then we will check if the user wins the game or not.

### Steps to Build a Python Tic Tac Toe Game
The steps are mentioned as below, 
* Create the display window for our game.
* Draw the grid on the canvas where we will play Tic Tac Toe.
* Draw the status bar below the canvas to show which player’s turn is it and who wins the game.
* When someone wins the game or the game is a draw then we reset the game.

We need to run our game inside an infinite loop. It will continuously look for events and when a user presses the mouse button on the grid we will first get the X and Y coordinates of the mouse. Then we will check which square the user has clicked. Then we will draw the appropriate ‘X’ or ‘O’ image on the canvas.

[Code](https://github.com/alinauman/Tic_Tac_Toe/blob/main/main.py)

This will be the starting image of the game
![Main Page](https://github.com/alinauman/Tic_Tac_Toe/blob/main/tic%20tac%20opening.png)
