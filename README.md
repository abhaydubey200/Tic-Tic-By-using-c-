Tic Tac Toe Game
This is a simple command-line implementation of the classic Tic Tac Toe game in C++.

Description
Tic Tac Toe is a two-player game where each player takes turns marking spaces in a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game. If the grid is filled without any player achieving a winning combination, the game is a draw.

This implementation allows two players to play Tic Tac Toe on the console. Players take turns entering the row and column of their move, and the game continues until one player wins or the board is full.

Features
Simple command-line interface.
Supports two players.
Validates player moves to ensure they are within the bounds of the board and not already occupied.
Checks for a winning condition after each move.
Detects a draw if the board is filled without a winner.
How to Play
Clone the repository or download the source code.
Compile the source code using a C++ compiler.
Run the executable file.
Follow the prompts to enter the row and column of your move.
The game will continue until one player wins or the board is full.
Usage
bash
Copy code
$ g++ tic_tac_toe.cpp -o tic_tac_toe
$ ./tic_tac_toe
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

