Methodology
Game Setup

Uses a 3x3 matrix to represent the board.
AI ("X") and Human ("O") take turns.
Game Flow

User Move → Input a number (1-9).
Check for Win/Draw.
AI Move → Uses Minimax to pick the best move.
Repeat until a win or draw occurs.
AI Decision (Minimax Algorithm)

Base Cases: AI wins (+1), Human wins (-1), Draw (0).
Recursion: Tries all possible moves, evaluates the best one.
Optimal Move Selection: AI picks the max score, Human picks min.

Output Example
Game Start:
markdown
Copy
Edit
 | | 
-----
 | | 
-----
 | | 
User Move (O selects 5):
markdown
Copy
Edit
 | | 
-----
 |O| 
-----
 | | 
AI Move (X picks best option):
markdown
Copy
Edit
 | |X
-----
 |O| 
-----
 | | 
Final Outcome:
AI Wins: "AI wins!"
Human Wins: "Congratulations, you win!"
Draw: "It's a draw!"
