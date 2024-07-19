# tic-tac-toes
Tic-Tac-Toe Game Description;

This Python implementation of Tic-Tac-Toe provides a classic two-player experience where each player takes turns marking 'X' or 'O' on a 3x3 grid. The game starts with an empty board displayed to the players. Players alternate turns until one player wins by getting three of their marks in a row (horizontally, vertically, or diagonally), or the game ends in a draw if there are no more empty spaces left.

Key Features:

Board Display: The game begins by displaying an empty 3x3 grid, with each cell numbered for easy reference (e.g., 1-9).

Player Input: Players are prompted to enter a number corresponding to the cell where they want to place their mark ('X' or 'O'). Input validation ensures that only valid moves (empty cells) are accepted.

Turn Alternation: Turns alternate between Player 1 ('X') and Player 2 ('O'). Each player sees the updated board after their move.

Winning Condition: After each move, the program checks if the move results in a winning combination. If a player has three marks in a row, they win the game.

Draw Condition: If no player wins and the board is filled with marks (all cells are occupied), the game declares a draw.

Restart Option: After the game ends (either in a win or a draw), players have the option to restart and play again.

Implementation Details:

Data Structures: The board is represented using a list of strings, where each string represents a cell ('X', 'O', or ' ' for empty).

Functions: The game logic is modularized into functions such as display_board(), check_winner(), player_move(), and is_board_full() to improve readability and maintainability.

Input Handling: The program handles user input, ensuring that only valid moves within the range (1-9) and on empty cells are accepted.

Error Handling: Error handling is implemented to manage unexpected inputs gracefully, prompting the player to enter a valid move.

Conclusion:
This Python-based Tic-Tac-Toe game encapsulates the essence of the classic game, providing an accessible and enjoyable experience for players. It showcases fundamental programming principles while delivering a polished and interactive gameplay environment.

CREDITS:
https://github.com/aqeelanwar
