# multiagents

Two AI agents with different LLMs simulating a chess game with Agentic capabilities.
The final score provides the evaluation of the winner based on the following assumptions:

Checkmate detection: It identifies if the game ends with a checkmate.
Draw conditions: It checks for a stalemate, insufficient material, or other draw conditions.
Material evaluation: It sums up the values of pieces each player has on the board to give a simple score.

## Requirements:
pip install IPython python-chess autogen typing_extensions

