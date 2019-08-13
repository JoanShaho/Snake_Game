# Snake_Game

This a recreation of the Snake game with some variations.

- **Snake**
  - The snake is modelled through a list of BodyPart objects.
  - The head and tail have their own variables as they are used when the snake eats the point or hits the border or its body.

- **Points**
  - There are two types of points in the game:
      - The main point, which is red, is the one that gives the player a point and increases the snake's length by one
      - The special point, which is blue, can have three functions:
          1. Doubles the current points
          2. Halves the current points
          3. Kills the snake

- **Additional Functionality**
  - The player can: 
      - save the current state of the snake, which includes the position and velocity of each body part, the position of the                       points, and the score
      - load the last saved state of the snake
      - pause and unpause the game
      - reset the game
