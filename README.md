# multiagents

Two AI agents with different LLMs with Agentic capabilities simulate a chess game.<br />
The final score provides the evaluation of the winner based on the following assumptions:<br />
<br />
Checkmate detection: It identifies if the game ends with a checkmate.<br />
Draw conditions: It checks for a stalemate, insufficient material, or other draw conditions.<br />
Material evaluation: It sums up the values of pieces each player has on the board to give a simple score.<br />

## Requirements:
pip install IPython python-chess autogen typing_extensions

## Set your LLM Keys:
echo 'export OPENAI_API_KEY="your_actual_openai_api_key_here"' >> ~/.bashrc<br />
<br />
Notes:<br />
Replace "your_actual_openai_api_key_here" with your actual OpenAI API key.<br />
Run source ~/.bashrc to reload the startup file and apply the changes immediately.<br />
