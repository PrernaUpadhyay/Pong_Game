



# Pong Game


This is a simple Pong game implemented using Python's `turtle` module. The game allows two players to control paddles on the screen, with the objective of hitting the ball back and forth. The game tracks scores for both players.

## Features

- Two paddles (left and right) controlled by keyboard keys.
- Ball movement with bouncing off walls and paddles.
- Scoring system to keep track of each player's score.
- The game ends when either player misses the ball.



## Controls

- **Right Paddle (Player 1)**:
  - Move Up: `Up Arrow`
  - Move Down: `Down Arrow`

- **Left Paddle (Player 2)**:
  - Move Up: `A`
  - Move Down: `S`

## Game Structure

### 1. Main Game

The main game file sets up the screen, handles the game loop, and controls paddle movement and scoring. It uses classes to implement the game logic, providing an interactive experience.

### 2. Paddle Class

The `Paddle` class controls the paddles' attributes and movements on the screen, allowing players to interact with the game seamlessly.

### 3. Ball Class

The `Ball` class manages the ball's movement and collision detection, ensuring that the ball bounces off walls and paddles effectively.

### 4. Scoreboard Class

The `Scoreboard` class tracks scores for both players and displays them on the screen, adding a competitive element to the game.



