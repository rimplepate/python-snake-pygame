# python-snake-pygame
Snake Game – Portfolio Project
A classic, interactive Snake Game built using Python and the Pygame library. This project demonstrates core game development concepts including event handling, coordinate-based movement, and collision detection.

Features
Dynamic Scoring: Your score increases every time the snake consumes food.

Game Over Screen: Displays your final score and offers options to restart or quit.

Smooth Controls: Utilizes responsive keyboard input for navigation.

Clean Visuals: Features a 600x400 window with clear color coding for the snake (green) and food (red).

Prerequisites
Before running the game, ensure you have Python installed on your system. You will also need to install the Pygame library:

Bash
pip install pygame
How to Run
Clone this repository or download the snake_game.py file.

Open your terminal or command prompt.

Navigate to the directory containing the file.

Run the following command:

Bash
python snake_game.py
Controls
Once the game starts, use your keyboard to control the snake:

Arrow Keys: Move the snake Up, Down, Left, or Right.

'C' Key: When the game is over, press C to play again.

'Q' Key: When the game is over, press Q to quit the application.

Rules
Objective: Eat the red food blocks to grow your snake and increase your score.

Death Conditions:

Hitting the boundaries of the game window.

Colliding with the snake's own body.

Technical Details
Window Size: 600x400 pixels.

Block Size: 20 pixels.

Frame Rate: 12 FPS (Clock tick) for consistent gameplay speed.
