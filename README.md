# Snake Game 🐍

This is a classic Snake Game built using Python and the Turtle Graphics module. The game follows the traditional rules where the snake grows in size as it eats food, and the player must avoid collisions with walls and the snake's own body.

## Features
- **Snake Movement**: Control the snake using arrow keys (`Up`, `Down`, `Left`, `Right`).
- **Food Consumption**: The snake consumes food, grows in size, and the score increases.
- **Collision Detection**:
  - Game ends if the snake hits the wall.
  - Game ends if the snake collides with itself.

## Code Overview
The project is divided into the following files:
1. **`main.py`**: The game loop, event listeners, and collision logic.
2. **`snake.py`**: Defines the Snake class, handling movement, growth, and segment management.
3. **`food.py`**: Manages the food object, including its random placement on the screen.
4. **`scoreboard.py`**: Displays the player's score and handles game-over messages.

### Core Python Concepts Applied
- **OOP (Object-Oriented Programming)**:
  - Classes like `Snake`, `Food`, and `Scoreboard` encapsulate specific functionalities.
- **Turtle Graphics**:
  - Used for rendering the snake, food, and scoreboard.
  - `Screen` is used for setting up the game window and listening for user inputs.
- **Collision Detection**:
  - Calculated using distance between objects (`distance` method).
- **Game Loop**:
  - `while` loop to keep the game running, with periodic screen updates (`screen.update` and `time.sleep`).
