# Tic-Tac-Toe (3×3) – Java Console Application

## 📌 Project Overview

This project is a **console-based 3×3 Tic-Tac-Toe game** developed in **Java**. It allows two players to play alternately using the command line. The program validates user input, updates the game board dynamically, detects winners or draw conditions, and handles invalid inputs gracefully.

The project demonstrates strong fundamentals of **Java programming**, including arrays, loops, conditionals, exception handling, and modular design using methods.

---

## 🎮 Game Features

- Two-player gameplay (Player X vs Player O)
- Turn-based system (X always starts first)
- Real-time board display after every move
- Input validation:
  - Prevents invalid slot numbers
  - Prevents overwriting occupied slots
  - Handles non-integer input safely
- Automatic detection of:
  - Winning conditions
  - Draw situations

---

## 🛠️ Technologies Used

- **Programming Language:** Java  
- **Core Concepts:**  
  - Arrays  
  - Loops (`for`, `while`)  
  - Conditional statements  
  - Switch-case  
  - Exception handling (`InputMismatchException`)  
  - Static methods and variables  
  - Ternary operator  
- **Input Handling:** `java.util.Scanner`

---

## 🧩 Project Structure

```
TicTacToe/
│
├── TicTacToe.java   # Main Java source file
└── README.md        # Project documentation
```

---

## ▶️ How to Run the Project

### Prerequisites
- Java JDK 8 or higher installed
- Command Line / Terminal

### Steps

1. Clone or download the repository
2. Open a terminal in the project directory
3. Compile the program:
   ```bash
   javac TicTacToe.java
   ```
4. Run the program:
   ```bash
   java TicTacToe
   ```

---

## 📋 How the Game Works

1. The board is initialized with numbers **1–9**, representing available slots.
2. Player **X** makes the first move.
3. Players take turns entering a slot number to place their symbol.
4. After every move:
   - The board is displayed
   - The program checks for a winner or draw
5. The game ends when:
   - A player gets three symbols in a row, column, or diagonal
   - OR all slots are filled (draw)

---

## 🏆 Winning Conditions

The program checks **8 possible winning combinations**:
- 3 horizontal rows
- 3 vertical columns
- 2 diagonals

If all three positions in any combination contain:
- `"XXX"` → Player X wins
- `"OOO"` → Player O wins

---

## 🔍 Key Methods Explained

### `checkWinner()`
- Evaluates all winning combinations
- Determines if a player has won or if the game is a draw
- Returns:
  - `"X"` → X wins
  - `"O"` → O wins
  - `"draw"` → Draw
  - `null` → Game continues

### `printBoard()`
- Displays the current state of the board in a readable format

### `main()`
- Controls the game loop
- Handles user input
- Manages turns and game flow

---

## ❗ Input Validation & Error Handling

- Prevents entering numbers outside the range **1–9**
- Prevents selecting an already occupied slot
- Handles invalid (non-numeric) input using exception handling
- Ensures the program never crashes due to user mistakes

---

## 🚀 Future Enhancements

- Convert to Object-Oriented Design
- Add Single Player Mode (AI)
- Create GUI using Swing or JavaFX
- Add score tracking and replay functionality
- Support variable board sizes

---

## 👨‍💻 Author

**Chirag**  
Engineering Student | Java Developer  

---

## 📄 License

This project is open-source and free to use for learning, academic, and personal projects.

