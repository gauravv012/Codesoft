# CodeSoft Internship Projects 🚀

This repository contains the C++ projects developed as part of the CodeSoft internship program. Each task is designed to strengthen basic programming and logical problem-solving skills.



## 🧩 Task 1: Number Guessing Game 🎯

The **Number Guessing Game** is a console-based C++ application where the computer randomly selects a number between 1 and 100, and the user tries to guess it. After each guess, the program provides feedback — whether the guess was too high or too low — until the correct number is guessed

### 🛠️ Tools & Technologies Used

- Language: C++
- Libraries Used:
  - `#include <iostream>` – for input/output operations
  - `#include <cstdlib>` – for random number generation
  - `#include <ctime>` – to seed the random number with system time


### 📌 How It Works

1. The program generates a random number between 1 and 100.
2. The user is prompted to guess the number.
3. After each guess:
   - If too low: it prompts “Too low! Try again.”
   - If too high: it prompts “Too high! Try again.”
4. When the correct number is guessed, the program congratulates the user and ends.

---

# 🔢 Task 2 - Simple Calculator (C++) – CodeSoft Internship

This is Task 2 of my internship at CodeSoft. The project is a Simple Calculator built using C++ that allows users to perform basic arithmetic operations: Addition,Subtraction, Multiplication, and Division.

## 📌 Features
- Performs operations based on user input:
  - ➕ Addition
  - ➖ Subtraction
  - ✖ Multiplication
  - ➗ Division (with zero division check)
- Uses switch-case for operator logic
- Handles invalid operators gracefully


## 💡 Concepts Used
- switch statements
- Input/output using cin and cout
- Basic arithmetic operations
- Error handling for division by zero

---

# 🎮 Task 3 - Tic Tac Toe Game (C++) – CodeSoft Internship

This is Task 3 of my internship at CodeSoft. The project is a Tic Tac Toe game implemented in C++, where two players can take turns to play on the same computer. The game includes full board rendering, win/draw detection, and replay capability.


## 📌 Features

- 🧠 *Two-player turn-based gameplay*
- 🖥 *Console-based UI* with board display
- ✅ *Win* and 🟰 *Draw* detection
- 🔁 *Play again* option
- ❌ Input validation for invalid or taken moves


## 💡 Concepts Used

- 2D arrays for the game board (board[3][3])
- Control structures (if, else, switch, while, do-while)
- Functions for modularity:
  - initializeBoard()
  - displayBoard()
  - placeMark()
  - checkWin()
  - checkDraw()
  - switchPlayer()

