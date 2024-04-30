Heuristic Function:
Implementation in the Code:

    In the code, the heuristic function is named evaluate_heuristic_for_game().
    This function evaluates the state of a mini Tic Tac Toe board represented by a string
    It assesses the distribution of player and opponent pieces on the board and assigns a score based on the presence of winning configurations.
    The function iterates through predefined winning configurations (e.g., three in a row, two in a row) and counts the occurrences of player and opponent pieces within these configurations.
    Based on these counts, it assigns a score reflecting the desirability of the board state for the player.

Algorithm (Minimax with Alpha-Beta Pruning):
Implementation in the Code:

    the code implements the Minimax algorithm with alpha-beta pruning in the functions min_turn() and max_turn().
    These functions perform recursive exploration of successor states, alternating between maximizing the player's score and minimizing the opponent's score 
    Alpha-beta pruning is applied during the search to efficiently prune branches of the game tree that are guaranteed to be irrelevant to the final decision.
    The algorithm maintains alpha and beta values representing the best possible scores found so far for the maximizing and minimizing players, respectively.
    It stops exploring certain branches of the game tree when it knows there's a better option, reducing unnecessary exploration.
    At leaf nodes or when reaching the depth limit of the search, the algorithm uses the heuristic function to evaluate the state of the game and estimate its desirability for the player.

Example:
    When the player (human or bot) interacts with the game, the algorithm determines the optimal move by exploring potential moves and outcomes.
    It evaluates the desirability of game states using the heuristic function and makes decisions accordingly.
    The algorithm efficiently prunes branches of the game tree using alpha-beta pruning, reducing computational complexity and improving performance.

![image](https://github.com/Sehal-22I-0604/AI_Assignment_2/assets/160497952/76c1cbcd-1cd0-42e0-81b0-d31f7cea4856)

![image](https://github.com/Sehal-22I-0604/AI_Assignment_2/assets/160497952/82335907-531e-4432-9a0d-3d9738acbf55)

![image](https://github.com/Sehal-22I-0604/AI_Assignment_2/assets/160497952/7b5a86f8-8ac9-4864-ae14-7c400997fc82)



I22-0604 Sehal Iqbal
K22-4066 Syed Ahmed Ishaq
