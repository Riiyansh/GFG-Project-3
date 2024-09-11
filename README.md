```markdown
# Tic Tac Toe Game

This repository contains a simple implementation of the classic Tic Tac Toe game in C++. The game allows a human player to compete against a computer opponent using the minimax algorithm for AI decision-making.

## Features

- Play against a computer .
- AI opponent uses the minimax algorithm for optimal moves.
- Simple command-line interface for user interaction.
- Displays the game board after each move.

## Getting Started

### Prerequisites

- A C++ compiler (e.g., g++, clang++)
- Basic understanding of how to compile and run C++ programs.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Riiyansh/GFG-Project-3.git
   cd tic-tac-toe
   ```

2. Compile the code:
   ```bash
   g++ -o tic_tac_toe main.cpp
   ```

3. Run the game:
   ```bash
   ./tic_tac_toe
   ```

### How to Play

1. When prompted, choose whether you want to start first.
2. Enter a cell number from 1 to 9 to place your move as 'X'.
3. The computer will respond with its move as 'O'.
4. The game continues until there is a winner or a draw.
5. After the game ends, you can choose to play again or quit.

## Game Board Representation

The game board is represented as follows:

```
    1 | 2 | 3
    ---------
    4 | 5 | 6
    ---------
    7 | 8 | 9
```

## Game Logic

- The game checks for winning conditions after each move:
  - Rows
  - Columns
  - Diagonals
- If all cells are filled without a winner, the game declares a draw.

## Author

- Riyansh - [Your GitHub Profile](https://github.com/Riiyansh)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the open-source community for their contributions and resources that helped in developing this project.
```
