🎰 Python Slot Machine Game

A simple command-line slot machine game built with Python. This project demonstrates basic Python programming concepts such as functions, loops, user input handling, and list manipulation. It's a great beginner-friendly project and a fun way to understand core logic building.

------------------------------------------------------------

📌 Features

- Deposit virtual money to start playing.
- Choose how many lines (up to 3) you want to bet on.
- Set a custom bet amount per line.
- Spin the slot machine and win if you hit matching symbols on a line.
- Displays total winnings and winning lines.
- Balance updates after every spin.
- Option to quit the game at any time.

------------------------------------------------------------

🧠 Game Rules

- The slot machine is a 3x3 grid.
- You can bet on 1 to 3 horizontal lines.
- If all three symbols on a line match, you win.
- Payout depends on the symbol's value:

  Symbol | Count in Pool | Value Multiplier
  -------|----------------|------------------
  A      | 2              | 5× bet
  B      | 4              | 4× bet
  C      | 6              | 3× bet
  D      | 8              | 2× bet

------------------------------------------------------------

🚀 How to Run

1. Clone the repository:

   git clone https://github.com/your-username/slot-machine-game.git
   cd slot-machine-game

2. Run the Python script:

   python slot_machine.py

------------------------------------------------------------

🧾 Example Gameplay

What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20

A | B | C
A | B | C
D | C | D

You won $30.
You won on lines: 1

Current balance is $110
Press enter to play (q to quit).

------------------------------------------------------------

🛠️ Built With

- Python 3.x
- Standard Library (no external packages)

------------------------------------------------------------

📁 File Structure

slot-machine-game/
├── slot_machine.py     # Main game logic
└── README.txt          # Project documentation

------------------------------------------------------------

🎓 Educational Value

This project is ideal for learning:
- Functions and control flow
- Input validation
- Randomization
- Data structures like lists and dictionaries
- Terminal-based interactivity

------------------------------------------------------------

📜 License

This project is licensed under the MIT License.

------------------------------------------------------------

🙋‍♂️ Author

Krishna Teja

Feel free to fork this repo, give it a ⭐, or suggest improvements!