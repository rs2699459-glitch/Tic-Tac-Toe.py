# Tic-Tac-Toe.py
A simple two-player Tic-Tac-Toe game in Python. Play in the console, take turns as X and O, and get instant win or draw results. Includes input validation and a play-again option.

Tic-Tac-Toe

A two-player, console Tic-Tac-Toe game written in Python 3. Player X goes first. Choose board positions 1 through 9; the board is displayed after each move. The game checks all eight winning lines, rejects invalid or occupied positions, reports draws, and lets players start another round.

## Run

Requires Python 3. Open a terminal in this folder and run:

```sh
python tic_tac_toe.py
```

On some systems, use `python3 tic_tac_toe.py` instead.

## Board positions

```text
 1 | 2 | 3
---+---+---
 4 | 5 | 6
---+---+---
 7 | 8 | 9
```

## Example

```text
Player X, choose a position (1-9): 1
Player O, choose a position (1-9): 4
```

The game asks `Play again? (y/n)` after a win or draw.