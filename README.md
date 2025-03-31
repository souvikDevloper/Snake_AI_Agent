Snake AI Agent using Deep Q‑Learning
This repository contains a full‑stack project where an AI agent is trained to play the classic Snake game using deep reinforcement learning. The implementation leverages PyGame for the game environment and PyTorch for building and training the Deep Q‑Network (DQN). The project is designed to showcase best practices in system design, clean code architecture, and scalable reinforcement learning solutions—making it a great portfolio piece for MAANG recruiters.

Features
Game Environment:

Classic Snake gameplay implemented using PyGame.

Real‑time rendering, score updates, and collision detection.

Deep Reinforcement Learning:

DQN model built in PyTorch.

Experience replay and epsilon‑greedy action selection.

Continuous training loop with both short‑term and long‑term memory updates.

Extensibility & Documentation:

Modular code structure separating the game logic, agent behavior, and model training.

Extensive inline comments and detailed documentation.

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/souvikDevloper/snake_Ai_Agent.git
cd snake-ai-agent
Install Dependencies:

Ensure you have Python 3.6+ installed. Then run:

bash
Copy
Edit
pip install -r requirements.txt
Dependencies include:

PyGame

PyTorch

NumPy

Usage
Play the Game Manually:
To run a manual version of the game (for testing the UI):

bash
Copy
Edit
python snake_game_human.py
Train the AI Agent:
To start training the AI agent using Deep Q‑Learning:

bash
Copy
Edit
python agent.py
The training loop will print out episode details (game count, score, record score) and continuously update the model.

Code Structure
game.py
Contains the full implementation of the Snake game environment, including rendering, input handling, and game state management.

agent.py
Implements the AI agent which interacts with the game environment. Handles state extraction, action selection (epsilon‑greedy), memory storage, and both short‑term and long‑term training.

model.py
Defines the neural network architecture (a simple feed‑forward DQN) used for approximating Q‑values.

helper.py
Includes utility functions such as plotting training progress and other helper methods.

snake_game_human.py
A script to run the game in manual mode for a live demo.

Contributing
Contributions are welcome! Please fork the repository and open a pull request with your improvements or suggestions.

License
This project is licensed under the MIT License. See the LICENSE file for details.

