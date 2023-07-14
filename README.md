# Reinforcement Learning project for beginners - Chess Agent

Welcome to my Reinforcement Learning project focused on developing an RL agent capable of playing chess at a strategic level. This project was part of my Master's degree class in Reinforcement Learning.

Chess has long been considered a benchmark for measuring AI capabilities, and this work aims to leverage the power of RL to create an intelligent agent that can make optimal decisions in complex chess positions. By combining the principles of reinforcement learning with the rich strategic domain of chess, I wanted to explore new approaches to create the most effective chess player.

## 1. Project Objectives:

* Train an RL agent to play chess: The primary objective of this project was to develop an RL agent that can play chess at a high level of proficiency. The agent should be capable of evaluating chess positions and making strategic decisions.

* Optimize decision-making using RL algorithms: I explored different RL algorithms, to train the agent and compared and analised their effectiveness in learning and decision-making capabilities in the context of chess.

* Use a challenging chess environment: Use a comprehensive environment for the agent to interact with, representing the rules and dynamics of chess. This environment will provide a realistic and challenging setting for the agent's training and evaluation.

* Evaluate and benchmark performance: Assess the performance of the RL agent against different benchmarks from an existing chess engine, here namely the Stockfish chess engine.

## 2. Running the code
For creating the chess environment several libraries are used. Install beforehand following libraries:
```
pip install gym
pip install gym_chess
pip install chess
```
For the agent and to play against Stockfish following libraries are needed:
```
pip install stockfish
pip install torch
```
You can download the Stockfish agent here: https://stockfishchess.org/
