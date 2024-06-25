# Connect 4 Game with AI

## Description
This Python implementation of Connect 4 features an AI opponent using the minimax algorithm with alpha-beta pruning. The game interface is built using Pygame.

## Features
- Two-player game: Human vs AI
- AI opponent using minimax algorithm with alpha-beta pruning for optimal moves
- Simple and interactive graphical user interface

## Requirements
- Python 3.x
- NumPy
- Pygame

## Game Rules
- Played on a vertical board with 7 columns and 6 rows.
- Players take turns dropping discs from the top into a column.
- Discs fall straight down, occupying the lowest available space.
- Objective: Connect four discs of the same color vertically, horizontally, or diagonally before your opponent.

## Minimax Algorithm with Alpha-Beta Pruning
The AI opponent uses the minimax algorithm with alpha-beta pruning:
- **Tree Representation**: Generates a tree of all possible moves up to a specified depth.
- **Maximizing and Minimizing**: AI maximizes its score while minimizing potential losses.
- **Evaluation Function**: Scores board states at the maximum depth using a heuristic.
- **Alpha-Beta Pruning**: Reduces unnecessary branches in the search tree, optimizing performance.

### How Minimax Works:
1. **Tree Representation**: Generates a tree of all possible moves up to a certain depth.
2. **Maximizing and Minimizing**: AI maximizes its score (maximizing player) while the human player minimizes the AI's score (minimizing player).
3. **Evaluation Function**: At the leaves of the tree (depth limit), evaluates the board using a scoring function.
4. **Alpha-Beta Pruning**: Reduces nodes evaluated by pruning branches that cannot affect the final decision.


### Here is a simplified diagram of the minimax algorithm:


![minmax](https://github.com/Rawan-AbdElmoneim/connect-4-AI/assets/142115846/e8764aa3-a395-405d-b2f6-d9459f52f061)

