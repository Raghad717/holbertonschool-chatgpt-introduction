# Enhancing Code Quality and Efficiency with ChatGPT

##  Project Overview
This project demonstrates how ChatGPT can be used to improve **code quality** through **debugging**, **error handling**, and **documentation** across multiple programming scenarios.  
The tasks simulate common real-world issues developers face and show how AI can help identify bugs, improve robustness, and produce clearer, more maintainable code.

All exercises focus on core software development skills such as logical debugging, user input validation, game state handling, and clean documentation.

---

##  Objectives
- Use ChatGPT to identify and fix logical and runtime errors
- Improve program stability using proper error handling
- Validate user inputs to prevent crashes and unexpected behavior
- Add professional documentation to Python code
- Demonstrate AI-assisted problem solving in realistic coding scenarios

---

##  Tasks Overview (0–6)

###  Debugging – Python Factorial (Iterative)
**File:** `factorial.py`

**Issue:** Infinite loop caused by a missing update of the loop variable.

**Fix Applied:**
- Decremented the loop counter inside the loop to ensure proper termination.

**Outcome:**
- Correct factorial calculation  
- Program terminates as expected

---

###  Debugging – Python Arguments
**File:** `print_arguments.py`

**Issue:** Script printed the Python file name along with arguments.

**Fix Applied:**
- Started iteration from `sys.argv[1]` instead of `sys.argv[0]`.

**Outcome:**
- Only user-provided arguments are printed

---

###  Debugging – HTML / JavaScript (Change Background Color)
**File:** `change_background.html`

**Issue:** The provided HTML/JS snippet was incomplete/incorrectly structured, which could prevent the click handler from working reliably.

**Fix Applied:**
- Rebuilt a valid HTML structure (head/style/body)
- Ensured the button exists before attaching the click listener
- Generated a valid **6-digit hex** color before applying it

**Outcome:**
- Background color changes successfully on button click

---

###  Debugging – Python Minesweeper (Win Condition)
**File:** `mines.py`

**Issue:** Game lacked a win condition and could not detect successful completion.

**Fix Applied:**
- Implemented a win-detection mechanism by checking revealed non-mine cells
- Added logic to end the game when all non-mine cells are revealed
- Added basic bounds validation for user-entered coordinates

**Outcome:**
- Game correctly identifies win and loss states

---

###  Documentation – Python Recursive Factorial
**File:** `factorial_recursive.py`

**Issue:** Indentation problems and missing required documentation.

**Solution:**
- Fixed indentation
- Added clear documentation with **three sections**:
  - Function description
  - Parameters
  - Returns

**Outcome:**
- Code is self-documented and easier to understand

---

###  Error Handling – Python Checkbook
**File:** `checkbook.py`

**Issue:** Program crashed on non-numeric input when converting user input to `float`.

**Fix Applied:**
- Added input validation and `try/except` handling for numeric conversion
- Displayed user-friendly error messages
- Ensured deposit/withdraw amounts are positive

**Outcome:**
- Program no longer crashes on invalid input  
- Improved user experience and robustness

---

### Debugging – Tic Tac Toe (Python)
**File:** `tic.py`

**Issues Identified:**
- Incorrect winner display due to turn switching logic
- No input validation (type/range) which could crash the program
- No draw condition when the board becomes full

**Fixes Applied:**
- Corrected winner logic (check win before switching players)
- Added input validation (numbers only, values 0–2)
- Implemented draw detection when no moves remain
- Prevented overwriting an occupied cell

**Outcome:**
- Fully functional game with win, lose, and draw states  
- Inputs are safely handled without crashing

---

## Introduction

This project showcases how AI-assisted development (using ChatGPT) can improve **code quality** through real debugging, error handling, and documentation exercises.  
Each task reflects common issues developers face—such as infinite loops, incorrect argument handling, broken UI interactions, missing win conditions in games, and unsafe user input—and demonstrates how to resolve them with clean, reliable solutions.

By completing these exercises, the project delivers a set of **robust, user-safe, and well-documented programs**, highlighting practical best practices and the value of integrating AI tools into everyday coding workflows.

## Author 
Raghad Almalki
