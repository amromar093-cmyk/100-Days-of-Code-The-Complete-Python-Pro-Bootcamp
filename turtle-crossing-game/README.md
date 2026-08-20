# Turtle Crossing

A Frogger-style road-crossing game built with Python's built-in turtle graphics module.

## Features

- Move the turtle up the screen using the Up arrow key
- Cars spawn at random and drive across the road
- Reaching the top of the screen advances you to the next level, resets your position, and speeds up the cars
- Live scoreboard tracks the current level
- Game over when a car collides with the player

## Project structure

```
turtle-crossing-game/
├── main.py           # Entry point - sets up the screen and runs the game loop
├── player.py          # Player class - movement and finish-line detection
├── car_manager.py     # CarManager class - spawns and moves the oncoming cars
├── scoreboard.py       # Scoreboard class - tracks and displays the level
├── requirements.txt
└── README.md
```

## Requirements

Python 3.x with Tk/Tkinter support (this ships with most standard Python installs; on Linux you may need to install it separately, e.g. `sudo apt install python3-tk`).

No third-party packages are required - turtle is part of the Python standard library.

## How to run

```
python3 main.py
```

## Controls

| Action  | Key      |
| ------- | -------- |
| Move up | Up arrow |

## How to play

Guide the turtle from the bottom of the screen to the top while dodging the oncoming cars. Reaching the top advances you to the next level, resetting your position and making the cars faster. Colliding with a car ends the game.
