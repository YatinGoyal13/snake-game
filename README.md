# Computer Vision Snake Game

The Computer Vision Snake Game is an interactive game implemented using computer vision techniques and the OpenCV library. The game utilizes the HandTrackingModule to detect and track the player's hand movements, allowing them to control the snake on the screen. The objective of the game is to guide the snake to eat food items displayed on the screen, which increases the snake's length. The game ends if the snake collides with its own body.

## Features

- Hand Tracking: The HandTrackingModule is used to detect and track the player's hand movements in real-time.
- Snake Movement: The player controls the snake by moving their hand. The snake follows the movement of the hand on the screen.
- Food Items: Food items are randomly generated on the screen for the snake to eat. When the snake consumes food, its length increases.
- Score Tracking: The game keeps track of the player's score, which is incremented every time the snake eats food.
- Game Over: If the snake collides with its own body, the game ends, and a game over screen is displayed. The player can restart the game by pressing the 'r' key.


## Usage

1. Launch the game by running the `snake_game.py` script.
2. Position your hand in front of the camera to start controlling the snake.
3. Move your hand to guide the snake towards the food items.
4. When the snake eats a food item, its length increases, and the player's score goes up.
5. Avoid collisions with the snake's own body. If the snake collides, the game ends, and the score is displayed.
6. To restart the game, press the 'r' key.

## Contributing

Contributions to the Computer Vision Snake Game project are welcome. Here are a few ways you can contribute:

- Report bugs and issues
- Suggest new features or enhancements
- Fix issues and submit pull requests

## License

The Computer Vision Snake Game project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.
