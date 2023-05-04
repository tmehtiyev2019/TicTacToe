# Generalized Tic Tac Toe (n * n)

Generalized Tic Tac Toe is an n * n board game where each player chooses one of the parts X or O, and then plays in an alternate order to place their choice on the board. A player wins when they are able to place m consecutive symbols (0s or Xs) in a contiguous sequence (row, column, or diagonal). The game may end in a draw when no one wins.

## Board Size (n) and Target (m)

Given `m` and `n`, the agent can play against another agent in an n * n board and tries to place m parts in a row to win.

## Code Overview

The code consists of the following main functions:

- `create_game(team_id_2, size, target)`: Creates a new game with the specified parameters.
- `make_move(game_id, move)`: Makes a move in the game with the specified game ID.
- `get_moves(game_id)`: Gets the list of moves for the specified game ID.
- `print_board(board)`: Prints the current game board.
- `is_winner(board, player, target)`: Checks if the given player has won the game.
- `is_full(board)`: Checks if the game board is full.
- `heuristic(board, player, opponent, target)`: Evaluates the current state of the game board.
- `get_valid_moves(board)`: Returns a list of valid moves for the current game board.
- `ai_move(board, max_depth, team_symbol, opponent_symbol, target)`: Determines the best move for the AI player.
- `main()`: The main function where the game is executed.

## How to run

1. Install Python 3.
2. Copy the code into a new file named `generalized_tic_tac_toe.py`.
3. Open a terminal/command prompt, navigate to the folder containing the `generalized_tic_tac_toe.py` file, and run `python generalized_tic_tac_toe.py`.
4. Follow the prompts to enter the required game parameters and start playing.
