# Connect-Four
Project for ECPE 170 : Computer Systems and Networks

## About
Creating game using a 6 x 9 board, with the first and last columns being populated with alternating Computer (C) and Human (H) tokens. The computer and Human alternate in placing a token in the board with the first person being determined by a coin toss with a seed set by the user inputting 2 numbers. The program will then determine if at all the computer or human creates a set of 5 tokens in any row then that player wins. The computer's turn will be generated by randomly selecting a column. All columns will be checked to determine whether or not the column can accept tokens. Winners of the rounds will be outputted at the end of each game.

## Implementation
This version of Connect Four (Really just connect five) was implemented in both C, using Visual Studio Code, and Assembly, using QtSPIM. 

## How to Run C Version
1. Before running, clean the directory with the command:
- make clean
2. Then compile the program with the command:
- make
3. Run the Compiled program with the command:
- ./main

## How to Run Assembly Version
1. With QtSPIM load the program by selecting:
- File -> Reinitialize and Load File
2. Run the Program from beginning to end by clicking:
- "Play" or F5
