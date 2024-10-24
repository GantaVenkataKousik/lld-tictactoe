# Tic-Tac-Toe Game (Low-Level Design)

A low-level design implementation of the classic Tic-Tac-Toe game, focusing on object-oriented principles and clean architecture.

## Features

- **Two-player game**: Supports a game between two players (X and O).
- **Grid-based gameplay**: Standard 3x3 grid layout.
- **Winning logic**: Checks for horizontal, vertical, and diagonal wins.
- **Draw detection**: Detects if the game ends in a draw when no moves are left.

## Game Design

The Tic-Tac-Toe game is built using object-oriented principles to create a clean and maintainable codebase. Key components include:

### Classes:
1. **Board**: Represents the game board, stores the state of the grid, and checks for win/draw conditions.
2. **Player**: Represents a player, either 'X' or 'O', and handles player actions.
3. **Game**: Manages the overall flow of the game, including turns, moves, and determining the winner or draw.

### Methods:
- `makeMove(position)`: Allows a player to mark a position on the board.
- `checkWinner()`: Verifies if there's a winner after each move.
- `isDraw()`: Checks if the game ends in a draw.

## How to Play

1. Player 'X' starts the game.
2. Players take turns marking their symbols ('X' or 'O') on the 3x3 grid.
3. The game continues until a player wins or the game ends in a draw.

## Installation

To run this project locally:

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project folder:
    ```bash
    cd tic-tac-toe-low-level-design
    ```

3. Follow instructions for compiling/running the project based on the specific programming language used (e.g., Java, Python).

## Contributing

Feel free to fork this repository and submit pull requests if you'd like to contribute to enhancing the game.

---
