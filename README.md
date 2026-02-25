# Object Oriented Programming of an m,n,k Tic Tac Toe Game

The objective is to run a customizable game with 2 players (the user and 1 of 3 automated computer players):

- User sets the conditions for the board with m, n, k as number of rows, numbers of columns, and number of win marks respectively.
- User selects a computer player difficulty (AI0, AI1, AI2):
  - AI0 randomly choose a position (Easy Mode).
  - AI1 chooses a position if it can win, otherwise chooses randomly (Medium Mode).
  - AI2 chooses a position if it can win or the user can win, otherwise chooses randomly (Hard Mode).

<br>
The second objective performs a statistical analysis of how the 3 computer players play against each other with varying board sizes.

- The probability of winning for the 3 competitions (AI0 vs AI1, AI0 vs AI2, AI1 vs AI2) were computed with repeated simulations. 

# Repository Contents

OOP_Project-mnk-TicTacToe.ipynb : Jupyter Notebook containing code split into 2 sections with first section consisting of the program to set up and execute the m,n,k tic-tac-toe game and the second section consisting of statistical analysis of the computer players' performance. 
