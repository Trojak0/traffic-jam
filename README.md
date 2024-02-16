# traffic-jam

Traffic Jam Game
This is a C++ program that implements a classic puzzle game called Traffic Jam. In this game, you are presented with a grid representing a traffic jam situation, where cars of various lengths are blocking the path of a red car that needs to exit the grid. Your goal is to maneuver the cars within the grid to create a path for the red car to exit.

Instructions:
Initialization:

When you run the program, you'll be prompted to enter the filename containing the initial state of the game board. This file should contain the setup of the traffic jam grid.
The program will read the file, populate the game board, and display the initial state of the grid.
Gameplay:

Once the game board is displayed, you'll need to input your moves to maneuver the cars within the grid.
Each move consists of three parts:
Car letter: The letter representing the car you want to move (e.g., A, B, C).
Number of moves: The number of grid spaces you want to move the car.
Direction: The direction in which you want to move the car (U for up, D for down, L for left, R for right).
Enter your move in the format: CarLetter NumberOfMoves Direction (e.g., A3R).
The program will validate your move and update the game board accordingly.
Winning:

The game is won when you successfully maneuver the red car to the rightmost position on the bottom row of the grid.
Once you win, a congratulatory message will be displayed, and the program will exit.
Quitting:

At any point during the game, you can enter Q to quit the game and exit the program.
Note:

The program does not use global variables and relies on functions to handle various aspects of the game mechanics.
Pay attention to the grid layout and plan your moves strategically to clear a path for the red car.
Enjoy playing Traffic Jam and have fun solving the puzzle!
