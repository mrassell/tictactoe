# 🎮 TicTacToe

**Class Project – Java Implementation**

---

## 📄 Project Overview

This is a console-based implementation of **Tic-Tac-Toe** written in Java. It supports:

- Two-player mode  
- Single-player mode vs. CPU  
- Quitting or forfeiting the game  
- Validation for invalid inputs and move handling

The program is designed with **simplicity and readability** in mind, using fundamental Java concepts such as:

- Arrays  
- Loops and conditionals  
- User input handling  
- Method-based structure and modularity

---

## ▶️ How to Play

- Choose between two-player, CPU, or quit modes at launch.
- Enter your move as a number from **1 to 9**, corresponding to the grid.
- Invalid inputs will trigger warnings. Three consecutive invalid inputs cause a forfeit.
- Enter **0** at any time to forfeit the game.

---

## 🛠️ Features and Structure

- `printBoard()` – Renders the game board with separators  
- `playerMove()` – Handles input, validation, and move logic  
- `cpuMove()` – Basic AI with win-check and random fallback  
- `makeMove()` – Updates the board with 'X' or 'O'  
- `checkWin()` – Evaluates win conditions (rows, columns, diagonals)  
- `isValidMove()` – Ensures moves are valid and untaken

---

## 📎 Notes

- The game uses `Scanner` for input handling.
- CPU attempts to win first, then makes a random move.
- Players are allowed 3 incorrect attempts before automatic forfeit.

---

## 🧑‍💻 Author

Maheen Rassell  
[GitHub Profile](https://github.com/mrassell)
