# Pong_game_python_Turtle

This Python Pong game is a simple implementation of the classic arcade game "Pong." It utilizes the Turtle graphics library for creating the game interface. The game features two paddles controlled by the player on the right and left sides of the screen, and a ball that bounces between them.

The game starts by initializing the screen and setting up the necessary components such as paddles, ball, and scoreboard. The screen is set to black with a size of 800x600 pixels. The paddles are created using the Paddle class, and the ball is created using the Ball class. The scoreboard keeps track of the score for each player.

The controls for the game are set using the `screen.onkey()` function, which binds specific keys to paddle movement functions. The right paddle moves up with the "Up" arrow key and down with the "Down" arrow key, while the left paddle moves up with the "w" key and down with the "s" key.

The game loop runs continuously until the `game_is_one` variable becomes False. Inside the loop, the ball moves by calling its `move()` method, and the screen is updated to reflect the new positions of the paddles and the ball.

Collision detection is performed to handle the bouncing of the ball. If the ball hits the top or bottom wall, it bounces by calling the `bounce_y()` method. If the ball collides with one of the paddles, it bounces by calling the `bounce_x()` method.

If the ball goes past the right paddle, the left player scores a point, and the ball is reset to its initial position. Similarly, if the ball goes past the left paddle, the right player scores a point. The scoreboard is updated accordingly.

The game ends when the `game_is_one` variable becomes False, which is not implemented in the given code. To exit the game, the player can click anywhere on the screen.

This Python Pong game provides a basic implementation of the classic game mechanics and can serve as a starting point for further enhancements and customization.
