Project Overview
This is a classic Tic Tac Toe (or Noughts and Crosses) game built using vanilla JavaScript. Two players take turns marking cells in a 3×3 grid with "X" and "O". The first player to align three marks in a row (horizontally, vertically, or diagonally) wins.

🎮 Gameplay Highlights
Turn-Based Logic: Player O starts first, and the turn alternates with each move.

Winning Conditions: Predefined win patterns check for 3 matching values in a row.

Game Controls:

New Game and Reset buttons restart the game.

Winner message is shown when someone wins.

UI Interaction:

Disables a cell after it's clicked.

Displays a congratulatory message when a player wins.

🛠️ Core Functions
checkWinner(): Checks the board after every move to determine a winner.

showWinner(winner): Displays the winning message and disables the board.

resetGame(): Resets the game board and hides the winner message.

enabledBoxes() & disabledBoxes(): Manage cell states.

🧠 Technologies Used
HTML – To define the grid and buttons.

CSS – (assumed, for styling the game).

JavaScript – To handle game logic and interactions.

