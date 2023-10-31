# snake-game
this made was done by using python programming language.

 Here's a description of the Snake game implemented in the provided Python code using the Turtle graphics library:

**Initialization and Setup:**

The game begins by importing the necessary libraries, setting up the game window, and initializing various game elements.
The game screen is created using Turtle graphics, with a green background and dimensions of 600x600 pixels.
The Snake's head, food, and the scoring pen are initialized.


**User Control:**

The snake's movement is controlled by the W, A, S, and D keys for up, left, down, and right, respectively.
Functions like go_up(), go_down(), go_left(), and go_right() handle these controls.
Game Loop:

The main game loop runs continuously and is responsible for updating the game's state and rendering the screen.
It constantly checks for user input and collision events.


**Collision Detection:**

The game checks for several collision events:
Collision with the screen border: If the snake goes out of bounds, it's game over.
Collision with the food: When the snake head touches the food, the snake grows and the food is relocated.
Collision with the snake's body: If the snake runs into itself, the game ends.


**Scoring and High Score:**

The player's score is displayed on the screen and is updated as they collect food.
A high score is also tracked, and it is updated when the player beats their previous high score.


**Snake Movement and Growth:**

The snake moves by shifting its segments in the direction of the head.
When the snake eats food, a new segment is added, effectively making the snake longer.


**Delay and Difficulty:**

The game progressively gets faster as the player's score increases by reducing the delay between frame updates.


**Game Over:**

When the game detects a collision (with the screen border or the snake's body), it briefly pauses, resets the snake's position, clears the body segments, and resets the score.


**Updating the Display:**

The display is updated with the snake's position, food location, and the current score.
The Turtle graphics library is used to draw the snake and food on the screen and to display the score.


**Endless Loop:**

The game continues to run in an endless loop until the player chooses to close the game window.
