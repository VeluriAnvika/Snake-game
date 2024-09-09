# AI Bot for Snake Game Using Searching Algorithms

Developed an artificial intelligence-based agent to play the Snake game using Python, implementing and comparing various searching algorithms, including A* Search, Depth First Search, Best First Search, and Random Search.


## Overview
---

This project implements an AI bot to play the classic Snake Game. The bot uses various algorithms to navigate the game grid, avoid collisions with walls or its own tail, and optimize its path to the food. The goal of the AI is to maximize the score by continuously growing the snake and surviving for as long as possible.
The Snake Game itself is built using Python and the Pygame library.
 
## Features

### Snake Game Implementation
The classic Snake Game created using Pygame, featuring movement controls, food generation, and increasing difficulty as the snake grows.

### AI Bot
The bot can autonomously play the game by determining the best path to the food while avoiding collisions.

### Algorithms Used

- A Pathfinding Algorithm*: Calculates the shortest and safest path to the food while avoiding obstacles.
- Breadth-First Search (BFS): Explores all possible moves layer by layer, ensuring that the shortest path is found, but without consideration for optimal future moves.

### Real-Time Visualization
The snake’s movements and the bot’s decisions are visualized in real time using Pygame, allowing users to observe the bot’s strategy.

### Adjustable Parameters
Game speed, grid size, and bot behavior can be fine-tuned to suit different scenarios or test cases.

## Future Enhancements

- Heuristic Optimization: Fine-tune the A* algorithm's heuristic to make it even more efficient.
- Obstacle Placement: Add additional obstacles or dynamic elements to test the bot's adaptability.
