# Tic-Tac-Toe Game

This is a simple implementation of the Tic-Tac-Toe game in Python. The game allows two players to play against each other: a human player and a computer player.

## Game Rules
Tic-Tac-Toe is a game played on a 3x3 grid. The goal of the game is to get three of your own marks (either "X" or "O") in a row, column, or diagonal. Players take turns placing their marks on empty spaces on the grid until one player wins or the game ends in a tie.

## Tutorial Source
This Tic-Tac-Toe implementation is derived from Kylie Ying's freecodecamp tutorial, which offers a comprehensive walkthrough for constructing the game. The tutorial covers the implementation of classes, methods, and AI algorithms, providing a solid foundation for building the game.

Link to the tutorial: [Tic Tac Toe AI with Python and the Minimax Algorithm](https://www.youtube.com/watch?v=8ext9G7xspg)

## How to Play
To play the game, follow these steps:

1. Clone the repository or download the source code files.
2. Make sure you have Python installed on your machine.
3. Open the terminal or command prompt and navigate to the directory where the files are located.
4. Run the game.py file using the command `python game.py`.
5. The game will start, and you will see the empty Tic-Tac-Toe board.
6. The game prompts the human player for their move. Enter a number from 0 to 8 to indicate the position where you want to place your mark.
7. The computer player will make its move automatically.
8. Continue taking turns until the game ends.
9. The game will display the winner or indicate a tie.

## Classes and Players
The game consists of three player classes: `HumanPlayer`, `RandomComputerPlayer`, and `GeniusComputerPlayer`. The `HumanPlayer` class allows a human to make moves by entering numbers through the command line. The `RandomComputerPlayer` class makes random moves, while the `GeniusComputerPlayer` class uses the Minimax algorithm to make optimal moves and cannot be beaten.

You can change the type of computer player by modifying the `o_player` variable in the `__main__` block of the game.py file. By default, the `GeniusComputerPlayer` is set as the opponent for the human player.


