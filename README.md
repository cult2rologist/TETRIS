[![Apache License 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

# TETRIS

This is an implementation of TETRIS in Python using:
1. Django framework.
2. Jinja2 as a template engine.
3. Threading module ("Rlock" is used for executing game logic, while "Timer" is employed for updating the game field on the frontend).

## How to play

Game controls:

⬆️: Rotate figure clockwise.

⬅️: Move figure left (one cell).

➡️: Move figure right (one cell).

⬇️: Soft drop (move figure down one cell). Hold for continuous soft drop.


1. Choose the battlefield size by typing a number from 3 to 5:
    - If you choose a battlefield size of 4 or 5, a winning combination will require 4 marks in a row, column, or diagonal.

2. To place a mark in a cell, enter two digits separated by a comma, like this: `row, column`:
    - Row and column indices start from 0. For example, to place a mark in the center of a 3x3 field, enter: `1, 1`.

3. After setting up the battlefield, you can type 'r' to restart or 'q' to quit the game.

Enjoy the game!

## Usage

1. Run the `tictactoe.py` file to start the game.
2. Follow the on-screen instructions to play.
3. Make your moves by entering the cell coordinates.
4. To restart the game or quit, follow the prompts on the screen.

## Files

- `tictactoe.py`: Contains the main game logic.
- `tictactoe_test.py`: Contains unit tests for each method in the `Game` class.

## Dependencies

This game requires Python 3.x to run.

## Contributors

- Ilya Makeev
- [Micellius](https://github.com/micellius) as a Mentor

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
