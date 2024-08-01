# multiagents

Two AI agents with different LLMs with Agentic capabilities simulate a chess game.<br />
The final score provides the evaluation of the winner based on the following assumptions:<br />
<br />
Checkmate detection: It identifies if the game ends with a checkmate.<br />
Draw conditions: It checks for a stalemate, insufficient material, or other draw conditions.<br />
Material evaluation: It sums up the values of pieces each player has on the board to give a simple score.<br />

## Requirements:
pip install IPython python-chess autogen typing_extensions

