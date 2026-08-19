# Pong

A classic two-player Pong game built with Python's built-in `turtle` graphics module.

## Features

- Two paddles, independently controlled
- Ball that speeds up slightly with every paddle hit and bounces off the top/bottom walls
- Live scoreboard for both players
- Ball resets to center after a point is scored

## Project structure

```
pong-game/
├── main.py         # Entry point - sets up the screen, game loop, and collisions
├── ball.py         # Ball class - movement, bouncing, and reset logic
├── paddle.py       # Paddle class - movement logic
├── scoreboard.py   # Scoreboard class - tracks and displays the score
├── requirements.txt
└── README.md
```

## Requirements

- Python 3.x with Tk/Tkinter support (this ships with most standard Python installs;
  on Linux you may need to install it separately, e.g. `sudo apt install python3-tk`)
- No third-party packages are required - `turtle` is part of the Python standard library

## How to run

```bash
python3 main.py
```

## Controls

| Player       | Move Up | Move Down |
|--------------|---------|-----------|
| Left paddle  | w       | s         |
| Right paddle | Up      | Down      |

Click anywhere in the game window to close it.

## How to play

The ball bounces between the two paddles. Miss it and your opponent scores a point.
The first player to rack up enough points (or just whoever's having more fun) wins.
