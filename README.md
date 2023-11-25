# **Tic-Tac-Toe Game**

This is a simple implementation of the Tic-Tac-Toe game in Python. The game allows two players to take turns, with one being the computer (AI) in a single-player mode.

## **How to Play**

1. Run the program by executing the `main()` function.
2. Choose between single-player (against the computer) or multiplayer.
3. Follow the on-screen instructions to make your moves.
4. The game will announce the winner or declare a draw.

## **Files**

- `tic_tac_toe.py`: Contains the main code for the Tic-Tac-Toe game.

## **Code Structure**

- **ConstBoard(board):** Function to display the current state of the Tic-Tac-Toe board.

- **User1Turn(board):** Function for the user's (X's) turn in multiplayer mode.

- **User2Turn(board):** Function for the second user's (O's) turn in multiplayer mode.

- **minimax(board, player):** Minimax algorithm implementation for the computer's (AI) turn.

- **CompTurn(board):** Function for the computer's (O's) turn using the minimax algorithm.

- **analyzeboard(board):** Function to check for a win or draw.

- **main():** The main function to initiate the game and handle user choices.

## **Usage**

1. Clone the repository: `git clone https://github.com/yourusername/tic-tac-toe.git`
2. Navigate to the project directory: `cd tic-tac-toe`
3. Run the program: `python tic_tac_toe.py`

## **Dependencies**

This program requires Python 3.x to run.
