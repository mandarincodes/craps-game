# Craps Game (Python OOP)

A command-line implementation of the classic casino dice game **Craps**, built using Object-Oriented Programming (OOP) and Python's `random` library. This project was developed as part of the TUMO Labs Guided Self-Learning track.

## Game Rules

1. **Initial Roll:** 
   - Rolling a **7** or **11** results in an **immediate win**.
   - Rolling a **2**, **3**, or **12** (Craps) results in an **immediate loss** (casino wins).
   - Rolling a **4, 5, 6, 8, 9, or 10** establishes that number as your **"goal"**.

2. **Subsequent Rolls:**
   - If a goal number was set, keep rolling until you either hit your goal number again (**win**) or roll a **7** (**loss**).

---

## Features

- **Object-Oriented Design:** Encapsulates game state and logic inside a clean `CrapsGame` class.
- **Randomized Dice Rolling:** Utilizes `random.randint(1, 6)` to simulate two fair six-sided dice.
- **Interactive Control Flow:** Leverages `while` loops and conditional statements to manage game progression based on the official rules.

---

## Requirements

- Python 3.x

---

## How to Run

1. Clone or download the repository to your local machine.
2. Open your terminal or command prompt in the project directory.
3. Run the script using Python:

```bash
python main.py
