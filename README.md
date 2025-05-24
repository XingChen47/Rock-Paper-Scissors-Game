# Rock Paper Scissors Game

A C++ program that allows you to play the classic Rock Paper Scissors game against the computer, with a user-friendly command-line interface. The program is cross-platform and works on Linux, Windows, and macOS.

## Features

- Play Rock Paper Scissors against the computer
- Random computer moves for fair play
- Simple command-line interface
- Cross-platform compatibility: Linux, Windows, macOS

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/XingChen47/Rock-Paper-Scissors.git
cd Rock-Paper-Scissors
```

### 2. Compile the program

#### **Linux/macOS**
```sh
g++ -o Rock_Paper_Scissors "RPS Game.cpp"
```

#### **Windows (using MinGW)**
```sh
g++ -o Rock_Paper_Scissors.exe "RPS Game.cpp"
```
*Make sure `g++` is available in your PATH. If using another compiler, adjust the command accordingly.*

## Usage

Run the program from the command line:

**Linux/macOS:**
```sh
./Rock_Paper_Scissors
```

**Windows:**
```sh
Rock_Paper_Scissors.exe
```


## How it Works

1. **User Input:** The program prompts you to enter your choice: rock, paper, or scissors.
2. **Computer Move:** The computer randomly selects its move.
3. **Determine Winner:** The program compares the choices to determine the winner and displays the result.
