# Go-Game! Let's Go!

A C++ implementation of a simplified Go game simulation using recursion for grid traversal algorithms.

## 📋 Description

This project implements core functionalities of the game of Go using recursion. It focuses on grid traversal algorithms to handle stone placement, capture detection, and move validation according to Go rules.

### 🎯 Learning Objectives
- Gain experience using recursion to solve structured grid-based problems
- Strengthen ability to organize code into clear, modular functions
- Implement grid traversal algorithms for game logic

## 🎮 Game Rules Implemented

### Key Concepts:
- **Cell**: Position on the board where a stone can be placed
- **Group**: Connected stones of the same color (horizontally/vertically)
- **Liberty**: Empty cell adjacent to a stone group
- **Capture**: Removing a group with zero liberties
- **Move Legality**: Validating moves according to Go rules

### Move Validation Conditions:
1. **Empty Cell**: Target cell must be empty
2. **Doom Prohibition**: Move cannot leave own group with zero liberties (unless capturing opponent)
3. **Repetition Prohibition (Ko)**: Cannot recreate previous board state


