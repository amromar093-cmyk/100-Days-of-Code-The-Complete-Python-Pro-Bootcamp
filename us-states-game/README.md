# U.S. States Game

A geography quiz built with Python's turtle graphics module. Type the name of a U.S. state and watch its name get stamped onto its correct spot on a blank map.

## Features

- Blank outline map of the United States as the game board
- Type a state name and its label is written at the correct coordinates on the map
- Tracks which states you've correctly guessed out of all 50
- Type "Exit" at any time to quit early - any states you hadn't guessed yet are saved to `states_to_learn.csv` so you can review them later
- Game ends automatically once all 50 states have been guessed

## Project structure

```
us-states-game/
├── main.py               # Entry point - sets up the screen and runs the game loop
├── 50_states.csv          # State names with their x/y coordinates on the map
├── blank_states_img.gif   # Blank U.S. map used as the game board
├── requirements.txt
└── README.md
```

## Requirements

Python 3.x with Tk/Tkinter support (this ships with most standard Python installs; on Linux you may need to install it separately, e.g. `sudo apt install python3-tk`), plus the `pandas` package.

## How to run

```
pip install -r requirements.txt
python3 main.py
```

## How to play

A text prompt repeatedly asks for the name of another state. Enter a state's name (any capitalization) and, if correct, its name is stamped on the map at the right location. Keep going until you've named all 50 states, or type "Exit" to stop early - the states you missed are written to `states_to_learn.csv`.
