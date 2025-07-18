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
