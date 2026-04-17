🧠 CSP-Based Sudoku Solver

This project is a Python-based Sudoku solver that uses Constraint Satisfaction Problem (CSP) techniques to efficiently solve Sudoku puzzles.

It demonstrates how intelligent search algorithms can be applied to reduce complexity and solve constraint-based problems.

🚀 Features
Backtracking search algorithm
Forward checking
AC-3 (Arc consistency algorithm)
MRV (Minimum Remaining Values) heuristic
Supports multiple difficulty levels (easy to very hard)
Clean terminal-based visual output
🛠️ Technologies Used
Python
Collections (deque)
Copy module
Colorama (for colored terminal output)
🧩 How It Works

The Sudoku puzzle is modeled as a Constraint Satisfaction Problem:

Each cell is a variable
Values (1–9) are domains
Constraints ensure no repetition in rows, columns, and 3×3 boxes

The solver improves efficiency using:

AC-3 → reduces inconsistent values early
Forward Checking → prevents invalid paths
MRV → selects the most constrained variable first
▶️ How to Run
Install dependencies:
pip install colorama
Run the program:
python sudoku_solver.py
📊 Output

The program displays:

Input Sudoku grid
Solved Sudoku grid
Performance statistics (calls & failures)
📌 Learning Outcome

This project helped in understanding:

Constraint Satisfaction Problems (CSP)
Backtracking optimization
Heuristic search techniques
Arc consistency (AC-3 algorithm)
👨‍💻 Author

Computer Science Student
Interested in Software Development and Problem Solving

⭐ If you like this project

Feel free to star the repository ⭐
