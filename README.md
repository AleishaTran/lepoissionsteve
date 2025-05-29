# Autonomous Pac-Man AI using Machine Learning

This project transforms the classic Pac-Man game by applying machine learning methods to enhance the AI agent’s ability to avoid ghosts and efficiently collect pellets.

## Project Summary

We successfully implemented a **Q-Learning framework** that allows the AI agent to learn optimal strategies through interaction with the game environment. The agent progressively improves by responding to a reward system, exploring the maze, and making better decisions over time.

Key features include:

- A Q-table based AI that learns to navigate dynamic obstacles (ghosts) and maximize pellet collection.
- Visualization tools integrated from the *Free Games* Python library to track AI behavior and game state.
- The game runs locally using the *turtle* graphics module, with simulations executed via Anaconda Prompt.
- Test code evaluates the agent’s performance by using the trained Q-table model to assess progress and success.
- Currently extending the project with a neural network implementation to further improve AI performance beyond traditional Q-Learning.
- The game environment is visualized in real-time using **Turtle graphics**, with Pacman represented as a custom GIF sprite.
- The state representation includes a local **3×3 perception grid**, simulating a limited field of view for the agent.
- Features a custom **20×20 tile-based maze** with defined walkable paths and walls.
- Uses Turtle-based visual representation for Pacman and static ghosts.
- Provides **local spatial awareness** through a 3×3 surrounding tile observation.
- Implements a **reward structure** that encourages exploration, discourages redundancy, and penalizes danger.
- Compatible with **Deep Q-Network (DQN)** agents using discrete action spaces.

## Challenge Addressed

Learning in dynamic, uncertain environments with obstacles and rewards — training an AI agent to make increasingly optimal decisions autonomously.

## Technologies Used

- Python
- Turtle graphics (for game visualization)
- Anaconda (environment management)
- Q-Learning reinforcement learning algorithm
- Free Games library (for visualization)
- Neural networks (in development)

---

This project demonstrates how reinforcement learning methods can be applied to classic games, offering insights into AI decision-making in complex, changing environments.

## HOW TO RUN THE CODE 
JUST RUN THE TRAIN.PY
