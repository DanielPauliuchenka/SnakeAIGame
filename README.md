# Snake Game with AI

This is my first attempt at building an AI for the classic Snake game using deep Q-learning. I made this project to explore reinforcement learning and learn how to train a neural network to play games.

---

## Features

- **AI-Driven Gameplay**: The AI learns to play the game using deep Q-learning.
- **Customizable Settings**: You can tweak the board size, speed, and other parameters.
- **Simple Graphics**: The game visuals are built with Pygame to keep things straightforward.

---

## Prerequisites

Before running the project, make sure you have Python 3.7 or higher installed. You also need to install the dependencies listed in the `requirements.txt` file.

### Dependencies
- matplotlib
- ipython
- numpy
- torch (PyTorch for training the AI)
- pygame

---

## Installation

1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd snake-ai
   ```

2. Set up a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate    # For Windows
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run

1. Run the AI agent:
   ```bash
   python agent.py
   ```

2. Sit back and watch the AI play the game!

---

## About the AI

The AI is powered by:
- **Deep Q-Learning**: A reinforcement learning algorithm that helps the agent learn by interacting with the game environment.
- **PyTorch**: Used to train the neural network that guides the AI.
![Snake Game AI in action (graph)](images/graph_game_ai.jng)

This project helped me get hands-on experience with AI and game development, and it was a great way to dive into deep learning concepts.

---

## License

This project is open-source and available under the MIT License. Check the `LICENSE` file for more information.

