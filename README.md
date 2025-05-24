# Rock-Paper-Scissors Game

A simple C++ console application that lets you play Rock-Paper-Scissors against the computer. The program presents a menu, accepts your input, generates a random computer move, and determines the winner each round.

## Features

- Play Rock-Paper-Scissors against the computer
- Menu-driven interface for playing or exiting
- Input validation for user choices
- Random computer selection (rock, paper, or scissors)
- Clear result display after each round
- Cross-platform: works on Linux, Windows, and macOS

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/XingChen47/Rock-Paper-Scissors-Game.git
cd Rock-Paper-Scissors-Game
```

### 2. Compile the program

#### **Linux/macOS**
```sh
g++ -o rps_game "RPS Game.cpp"
```

#### **Windows (using MinGW)**
```sh
g++ -o rps_game.exe "RPS Game.cpp"
```
*Make sure `g++` is available in your PATH.*

## Usage

Run the compiled program from your terminal:

**Linux/macOS:**
```sh
./rps_game
```

**Windows:**
```sh
rps_game.exe
```

Select "1" to play or "2" to exit. Enter your move as 'r' for rock, 'p' for paper, or 's' for scissors. The computer will randomly select its move. The program will display both choices and declare the winner.

**Example Output:**
```
****************************************
Welcome to the Rock-Paper-Scissors Game!
****************************************
1. Continue to play the game
2. Exit
****************************************
1
****************************************
Welcome to the Rock-Paper-Scissors Game!
****************************************
Please choose one of the following
'r' for rock
'p' for paper
's' for scissors
************************************
Enter your choice: 
r
********************************
Player1 made a choice of: Rock
********************************
Player2 made a choice of: Scissors
********************************
Player1 has won!
```

## Input Validation

- If you enter an invalid menu option or game move, the program will notify you and prompt again.

## Customization

You can change the game logic, number of rounds, or add new features by editing the source code.
