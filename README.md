# AI Minesweeper Game

An intelligent agent developed that uses logical reasoning and AI techniques to play the classic game of Minesweeper autonomously.

## Overview
The AI agent makes informed decisions based on the game state by:
- Using logical sentences to represent knowledge.
- Deducing safe moves and identifying mines.
- Dynamically updating its knowledge base after each move.

## Features
- **Intelligent Agent:** Capable of perception, decision-making, and action execution.
- **Logical Reasoning:** Uses a `Sentence` class to reason about the board state.
- **Interactive UI:** Built using `pygame` to visualize game play.

## Project Structure
- `minesweeper.py`: Contains the core game logic and the `MinesweeperAI` class.
- `runner.py`: The entry point script that initializes the game environment and AI agent.
- `assets/`: Contains images and fonts used for the UI.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the game: `python runner.py`
