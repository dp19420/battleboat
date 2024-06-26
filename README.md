## Battleboats Game

A simple Battleship game implemented in Python and deployed on Heroku.

### Features

- 10x10 grid for the game board
- Random placement of 7 ships on the computer's grid
- Input validation for row and column coordinates
- Tracking of hit and miss shots on the player's grid
- Countdown of remaining turns

### How to play

1. The game will randomly place 7 ships on a 10x10 grid.
2. Enter row and column numbers to fire shots.
3. Try to sink all 7 ships before running out of turns.

### Running the Game

The Game is deployed at:["Heroku"](https://battledingy-cdeb8d5d9b45.herokuapp.com/)

### Code

The code for the game is contained in the game.py file, which is deployed on Heroku.

- target_grid and aim_grid represent the computer's and player's grids.
- print_grid(grid) prints the given grid.
- place_ships(grid) randomly places ships on the grid.
- place_shot() prompts the user for row and column coordinates.
- sunk_ships(grid) counts the number of ships on the grid.
The main loop runs until the player wins or loses.
