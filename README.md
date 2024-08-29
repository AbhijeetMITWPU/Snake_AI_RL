# Snake AI with Reinforcement Learning

## 🚀 Project Overview
This project implements a Snake AI using Reinforcement Learning, where the snake learns from its mistakes and improves with each penalty. The AI is trained using **Linear QNet** and **QTrainer**, employing deep Q-learning to develop strategic gameplay.

## 🎮 Features
- **Self-Learning AI**: The snake improves its performance by learning from penalties and rewards.
- **High Score Achievement**: After 100 games of training, the AI achieved a high score of 70, with potential for even higher scores.
- **Future Enhancements**:
  - Avoid self-collision and prevent the snake from getting trapped in loops.
  - Optimize the pathfinding to the goal, making the AI even more efficient.

## 🛠️ Technologies Used
- **Python**: For core programming and AI implementation.
- **PyTorch**: Used for building and training the neural network.
- **Pygame**: For game development and visualization.
- **Numpy**: For efficient numerical computations.

## 📂 Project Structure
- `agent.py`: Contains the reinforcement learning agent using Linear QNet and QTrainer.
- `model.py`: Defines the neural network model and Q-learning trainer.
- `game.py`: Manages the Snake game logic, including AI integration and game rendering.
- `README.md`: This file, providing an overview of the project.

## 🧠 How It Works
The AI uses a deep Q-learning approach, where:
1. **State Representation**: The current state of the game (snake position, food position, etc.) is encoded.
2. **Action Selection**: The AI selects actions (move left, right, etc.) based on Q-values predicted by the neural network.
3. **Learning**: The AI updates its Q-values using rewards for good actions (e.g., eating food) and penalties for bad actions (e.g., hitting a wall).
4. **Experience Replay**: Past experiences are stored and replayed to stabilize learning.

## 🚧 Future Work
- **Self-Collision Avoidance**: Implementing logic to prevent the snake from colliding with itself or getting trapped in a loop.
- **Optimized Pathfinding**: Enhancing the AI to find the most efficient path to the goal.

## 🎯 Usage
Clone this repository and run the game:
```bash
git clone https://github.com/AbhijeetMITWPU/Snake_AI_RL
cd Snake_AI_RL
python agent.py
```
## 🔗 Links
**Project Repository**: https://github.com/AbhijeetMITWPU/Snake_AI_RL.<br>
**Connect with Me**: www.linkedin.com/in/singhabhijeet16.
