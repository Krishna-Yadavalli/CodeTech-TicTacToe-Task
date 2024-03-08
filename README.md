# CodeTech-TicTacToe-Task

Tic-Tac-Toe Game Documentation

Introduction
The Tic-Tac-Toe game is a classic two-player game where players take turns marking spaces on a 3x3 grid with their respective symbols (X or O). The objective of the game is to be the first to complete a row, column, or diagonal with their symbol.


Overview
This Java program implements a text-based version of the Tic-Tac-Toe game. It allows two players to play against each other: one player is represented by 'X', and the other by 'O'. The game board is displayed after each move, and players are prompted to enter their moves via the console.


Components
Main Class (TicTacToe):

This class contains the main method where the game execution begins.
It initializes the game board and manages the flow of the game.

Game Board:

The game board is represented as a 3x3 grid, displayed using a 2D array of characters.
The grid contains spaces for players to place their marks ('X' or 'O').

Player Input:

Players enter their moves by specifying the position on the grid where they want to place their mark.
Input validation ensures that players cannot select positions that are already occupied.

Winning Conditions:

The program checks after each move whether a player has won the game.
Winning conditions include completing a row, column, or diagonal with the same symbol.

Game Loop:

The game continues until a player wins or the board is full (resulting in a draw).
After each move, the program checks for a winner and alternates between players.

Functionality
Printing the Game Board:

The printBoard() method displays the current state of the game board after each move.

Placing Marks:

The placeValue() method updates the game board with the player's mark at the specified position.

Checking for a Winner:

The checkWinner() method examines the game board to determine if a player has won.
It checks all possible winning combinations (rows, columns, and diagonals).

Game Termination:

The game terminates when a player wins or when the board is full (resulting in a draw).
Upon termination, the program displays the winner or declares a draw.

Usage
Starting the Game:

Run the program, and the game will start automatically.
Players take turns entering their moves via the console.

Input Instructions:

Players enter their moves by specifying the position on the grid (1 to 9).
The game validates the input to ensure it's within the valid range and not already occupied.

Game Outcome:

The game continues until one player wins or the board is full.
After termination, the program displays the winner or declares a draw.

Conclusion
This Java program provides a fun and interactive way to play the classic Tic-Tac-Toe game in a text-based format. It offers a simple yet engaging gaming experience for two players, allowing them to test their strategic skills and compete for victory.
