# Snake-Game

This is a simple Snake game built with HTML, CSS, and JavaScript.

## index.html

This is the main HTML file for the game. It includes the following elements:

* The `<head>` section contains the title of the game, the stylesheet link, and the font awesome link.
* The `<body>` section contains the game wrapper, the game details, the play board, the controls, and the copyright.

The game wrapper is a div element that contains all of the other elements in the game. The game details div contains the score and the high score. The play board div is where the snake will be rendered. The controls div contains the four arrow icons that the user can use to control the snake. The copyright div contains the copyright information.

## style.css

This is the stylesheet for the game. It defines the styles for the game wrapper, the game details, the play board, the controls, and the copyright.

## script.js

This is the JavaScript file for the game. It includes the following functions:

* The `init()` function initializes the game. It creates the snake, the food, and the score. It also sets up the event listeners for the arrow keys.
* The `update()` function updates the game state. It moves the snake, checks for collisions, and increases the score if the snake eats food.
* The `draw()` function draws the game to the screen. It draws the snake, the food, the score, and the controls.
* The `keyDown()` function handles the key down event. It changes the direction of the snake if the user presses an arrow key.

## How to play the game

To play the game, use the arrow keys to move the snake. The goal of the game is to eat as much food as possible without running into yourself or the walls. The game ends when the snake runs into itself or the walls.

## Conclusion

This is a simple Snake game that can be played in the browser. It is a fun and challenging game that can be enjoyed by people of all ages.
