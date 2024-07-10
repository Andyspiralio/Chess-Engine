

# Python Chess Engine

A sophisticated chess engine implemented in Python, featuring dynamic move analysis and efficient decision-making strategies.

## Features

- **Pygame-based Interface**: Utilizes Pygame for a dynamic and interactive chess board visualization.
- **Minimax Algorithm**: Implements deep position evaluation and optimal move selection.
- **Greedy Algorithm**: Applies heuristic analysis of the board state for quick decision making.
- **Naive Pattern Matching**: Detects checkmate and stalemate scenarios efficiently.

## Technologies Used

- Python
- Pygame

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/python-chess-engine.git
   cd Chess-Engine
   ```

2. Install the required dependencies:
   ```
   pip install pygame
   ```

### Running the Chess Engine

Run the main script to start the chess engine:
```
python ChessMain.py
```

## How It Works

1. **Board Representation**: The chess board is represented using a 2D array, with pieces denoted by unique identifiers.

2. **Move Generation**: Legal moves are generated for each piece based on the current board state.

3. **Evaluation**: The minimax algorithm evaluates potential moves, looking several moves ahead to determine the best course of action.

4. **Heuristics**: A greedy algorithm is applied for quick heuristic analysis of the board state, assisting in move prioritization.

5. **Endgame Detection**: Naive pattern matching is used to efficiently detect checkmate and stalemate scenarios.

