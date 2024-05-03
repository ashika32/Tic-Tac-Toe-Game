# Tic-Tac-Toe-Game
 Tic-Tac-Toe is a classic two-player game where the objective is to form a line of three matching symbols (either “X” or “O”) on a 3x3 grid. Let’s dive into the details of how to create a simple Tic-Tac-Toe game in Java:

Game Rules:
Two players take turns to place their symbols (“X” or “O”) on the board.
The player who successfully forms a line (horizontally, vertically, or diagonally) wins.
If all cells are filled and no player has formed a line, the game ends in a draw.
Game Implementation: Below is a basic implementation of a Tic-Tac-Toe game in Java
Game Logic:
The checkWinner() method checks if any player has won or if the game ended in a draw.
The printBoard() method displays the current state of the board.
Sample Input and Output:
Players input the slot number (1 to 9) where they want to place their symbol.
The program alternates between “X” and “O” until a winner is determined or the game ends in a draw.
