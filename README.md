# Python Learning Log

Small console programs I wrote while learning the basics of **Python**: input and output, conditional statements, lists, loops and the `random` module. No external libraries are needed.

## Projects

| File | Project | Concepts |
|---|---|---|
| [`Treasure Island.py`](./Treasure%20Island.py) | Treasure Island | `input()`, nested `if`/`elif`/`else`, string methods |
| [`Paper, rock, scissors.py`](./Paper,%20rock,%20scissors.py) | Rock, Paper, Scissors | lists, `random`, comparing values, ASCII art |
| [`loop.py`](./loop.py) | PyPassword Generator | `for` loops, `random.choice()`, `random.shuffle()` |

### Treasure Island

A text adventure game. You start at a crossroad and make choices (left or right, wait or swim, which door to open) that lead either to the treasure or to the end of the game.

### Rock, Paper, Scissors

Play against the computer: type `0` for Rock, `1` for Paper or `2` for Scissors. The computer picks randomly, both choices are shown as ASCII art and the program announces the winner.

### PyPassword Generator

Asks how many letters, symbols and numbers the password should contain, picks random characters from each group, shuffles them and prints a new password.

## How to run

Requires Python 3.

```sh
python "Treasure Island.py"
python "Paper, rock, scissors.py"
python loop.py
```

## Author

Natalia Kowal
