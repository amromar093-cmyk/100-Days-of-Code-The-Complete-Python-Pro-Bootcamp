# Snake

A classic Snake game built with Python's built-in turtle graphics module.

## Features

- Classic snake movement controlled with the arrow keys
- Snake grows by one segment each time it eats food
- Food repositions to a random spot on the screen after being eaten
- Live scoreboard that tracks the current score
- Game over triggered by hitting the screen edge or colliding with itself

## Project structure

```
snake-game/
├── main.py           # Entry point - sets up the screen and runs the game loop
├── snake.py           # Snake class - movement, growth, and steering logic
├── food.py             # Food class - random placement on the board
├── scoreboard.py   # Scoreboard class - tracks and displays the score
├── requirements.txt
└── README.md
```

## Requirements

Python 3.x with Tk/Tkinter support (this ships with most standard Python installs; on Linux you may need to install it separately, e.g. `sudo apt install python3-tk`).

No third-party packages are required - `turtle` is part of the Python standard library.

## How to run

```
python3 main.py
```

## Controls

| Action | Key |
| --- | --- |
| Move up | Up arrow |
| Move down | Down arrow |
| Move left | Left arrow |
| Move right | Right arrow |

## How to play

Steer the snake around the board to eat the food. Each piece of food eaten grows the snake by one segment and increases the score. The game ends if the snake runs into the wall or into its own tail.
