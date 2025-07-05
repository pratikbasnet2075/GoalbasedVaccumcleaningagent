# Agent

Agents

This repository involve implementing different types of agents for a vacuum cleaning environment. Assume a 10x10 grid world with four cells, where each cell can be either clean or dirty. The vacuum cleaner can move up, down, left, or right, and can suck dirt to clean a cell. The agent's starting position is random, and the goal is to clean all cells efficiently.

Simple Reflex Agent

Implement a simple reflex vacuum cleaning agent that selects actions based solely on the current percept (whether the current cell is dirty or clean). If the cell is dirty, the agent sucks the dirt; otherwise, it moves to a random adjacent cell. Input: Current cell state (dirty or clean). Output: Action (suck, move up, move down, move left, move right). Requirement: Simulate the agent's behavior for 20 steps and display the grid state after each step.

Goal-Based Agent

Implement a goal-based vacuum cleaning agent that maintains an internal model of the grid to track which cells are dirty. The agent aims to clean all dirty cells and stops when the entire grid is clean. Use a simple search strategy (e.g., moving to the nearest dirty cell). Input: Current cell state and agent’s internal model of the grid. Output: Sequence of actions to achieve a clean grid. Requirement: Display the sequence of actions and the final grid state.

Utility-Based Agent

Implement a utility-based vacuum cleaning agent that assigns a utility score to actions based on cleanliness and movement efficiency (e.g., minimize movement steps). Define a utility function (e.g., +5 for cleaning a dirty cell, -1 for each move). The agent selects actions to maximize cumulative utility. Input:Current cell state and internal model of the grid. Output: Sequence of actions optimizing utility. Requirement: Display the actions, final grid state, and total utility score.
