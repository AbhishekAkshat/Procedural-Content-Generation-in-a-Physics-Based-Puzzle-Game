# Procedural Content Generation in a Physics-Based Puzzle Game

This project presents an interesting Procedural Level Generation algorithm set up in a physics-based puzzle game that is a cloned version of the popular Angry Birds game. We will be looking at two research questions firstly on Procedural Content Generation secondly on improving the Angry bird agent. 
In this project, we explain how the generator generates structures in interesting ways to make the game-play more challenging. Moreover, we also discuss on the agent’s engagement with these generated levels while trying to optimize the game-play by scoring more while using less number of birds. Various experiments were conducted and we were able to device some interesting and fun levels.

## Agents:

We tested our generated levels for various parameters, such as stability, difficulty or playability, etc.
For this, we tested the generated levels using two agents:

* Naive Agent
* Deep Q-Network Agent

This is done in order to be able to compare the performance of two different agents with different abilities on the same levels that were generated. We first set a baseline, and choose a Naive agent and then proceed onto testing on a slightly more complex and advanced agent i.e., Deep Q-Network agent that uses Deep Reinforcement Learning strategies for game play.
