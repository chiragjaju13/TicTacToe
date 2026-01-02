Tic-Tac-Toe (3×3) – Java Console Application
📌 Project Overview

This project is a console-based 3×3 Tic-Tac-Toe game developed in Java. It allows two players to play alternately using the command line. The program validates user input, updates the game board dynamically, detects winners or draw conditions, and handles invalid inputs gracefully.

The project demonstrates strong fundamentals of Java programming, including arrays, loops, conditionals, exception handling, and modular design using methods.

🎮 Game Features

Two-player gameplay (Player X vs Player O)

Turn-based system (X always starts first)

Real-time board display after every move

Input validation:

Prevents invalid slot numbers

Prevents overwriting occupied slots

Handles non-integer input safely

Automatic detection of:

Winning conditions

Draw situations

Clean and user-friendly console output

🛠️ Technologies Used

Programming Language: Java

Concepts Applied:

Arrays

Loops (for, while)

Conditional statements

Switch-case

Exception handling (InputMismatchException)

Static methods and variables

Ternary operator

Input Handling: java.util.Scanner

🧩 Project Structure
TicTacToe/
│
├── TicTacToe.java   # Main Java source file
└── README.md        # Project documentation

▶️ How to Run the Project
Prerequisites

Java JDK 8 or higher installed

Command Line / Terminal

Steps

Clone or download the repository

Open a terminal in the project directory

Compile the program:

javac TicTacToe.java


Run the program:

java TicTacToe

📋 How the Game Works

The board is initialized with numbers 1–9, representing available slots.

Player X makes the first move.

Players take turns entering a slot number to place their symbol.

After every move:

The board is displayed

The program checks for a winner or draw

The game ends when:

A player gets three symbols in a row, column, or diagonal

OR all slots are filled (draw)

🏆 Winning Conditions

The program checks 8 possible winning combinations:

3 horizontal rows

3 vertical columns

2 diagonals

If all three positions in any combination contain:

"XXX" → Player X wins

"OOO" → Player O wins

🔍 Key Methods Explained
checkWinner()

Evaluates all winning combinations

Determines if a player has won or if the game is a draw

Returns:

"X" → X wins

"O" → O wins

"draw" → Draw

null → Game continues

printBoard()

Displays the current state of the board in a readable format

main()

Controls the game loop

Handles user input

Manages turns and game flow

❗ Input Validation & Error Handling

Prevents entering numbers outside the range 1–9

Prevents selecting an already occupied slot

Handles invalid (non-numeric) input using exception handling

Ensures the program never crashes due to user mistakes

🚀 Future Enhancements (Optional)

Convert to Object-Oriented Design using separate classes

Add Single Player Mode (AI) using Minimax Algorithm

Create a GUI version using Swing or JavaFX

Add score tracking and replay functionality

Extend to variable board sizes (e.g., 4×4, 5×5)

👨‍💻 Author

Chirag
Engineering Student | Java Developer

📄 License

This project is open-source and free to use for learning, academic, and personal projects.
