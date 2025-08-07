# Command-Line Calculator

A simple, interactive Python-based command-line calculator that supports basic arithmetic operations. This tool runs in your terminal and allows users to perform calculations in a continuous loop until they choose to exit.

---

## Features

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)
- Input validation (non-numeric & division by zero)
- Looping menu until user exits

---

## Tools Required

- Python 3.x
- VS Code / any text editor
- Terminal / Command Prompt

---

##  Getting Started

### 1. Clone or Download the Project
You can either clone this repo or manually download the `calculator.py` file.


git clone https://github.com/yourusername/command-line-calculator.git
cd command-line-calculator

2. Run the Calculator
Make sure Python is installed on your system. Then open the terminal and run:


python calculator.py

Usage Example
Mathematics

--- Command-Line Calculator ---
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit
Enter your choice (1-5): 1
Enter first number: 5
Enter second number: 10
Result: 15.0

Project Structure

command-line-calculator/

calculator.py     # Main Python script
README.md         # Project documentation


 Code Structure
• Each operation is handled by a dedicated function:
○ add(x, y)
○ subtract(x, y)
○ multiply(x, y)
○ divide(x, y)

• A loop allows repeated use until the user exits.
• Basic error handling is included for invalid input and division by zero.

 To-Do (Optional Enhancements)
• Support for exponentiation, modulus
• Command-line arguments for one-off calculations
• Logging calculation history
• GUI version using Tkinter or PyQt



Author
Deepshikha
