
---

# ⚪⚫ Othello AI: Minimax, Alpha-Beta Pruning & Expectimax

This project is a comprehensive implementation of an **AI agent** to play the classic board game **Othello (Reversi)**. It explores various search algorithms and heuristic evaluation functions to create a challenging opponent.

## 📝 Project Overview

The goal of this assignment was to model Othello as a deterministic, perfect-information, 2-player, zero-sum game and implement several decision-making algorithms to find the optimal moves.

### Key Features:

* **Game Engine:** Complete implementation of Othello rules, including legal move detection, piece flipping, and game-over conditions.
* **Algorithms Implemented:**
* **Minimax:** Standard recursive search for optimal moves.
* **Alpha-Beta Pruning:** Optimized Minimax that prunes unnecessary branches to search deeper in less time.
* **Expectimax:** Designed for scenarios with uncertainty (though applied here to model different opponent behaviors).
* **Greedy & Random:** Baseline agents for performance comparison.


* **Evaluation Functions:** Advanced heuristics considering board control, corner occupancy, and mobility.
* **GUI:** An interactive Graphical User Interface (built with `tkinter`) to play against your AI in real-time.

## 🚀 Algorithms Comparison

The notebook includes a performance analysis of different agents:

* **Random Agent:** Easily defeated.
* **Greedy Agent:** Stronger than random, but lacks long-term strategy.
* **Minimax & Alpha-Beta:** The most challenging opponents. Alpha-Beta significantly reduces the search time (around 3 minutes compared to longer durations for raw Minimax).

## 🛠️ Requirements

To run the game and the GUI:

* `numpy`
* `tkinter` (usually comes pre-installed with Python)

```bash
pip install numpy

```

## 🎮 How to Play

1. Run the cells in `ex3_othello.ipynb`.
2. The GUI will launch, allowing you to choose your moves by clicking on the board.
3. Watch how the AI calculates its moves using the selected algorithm.

## 📊 Experimental Results

As recorded in the notebook, the AI agents (Minimax/Alpha-Beta) consistently win against human players or simpler strategies within a reasonable decision time (typically 3-5 minutes for a full game analysis).

---

