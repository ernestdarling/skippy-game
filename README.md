# Skippy Game

## Overview
Skippy game is a simple game of skipping obstacles. After starting the game, obstacles appear in the frame from right to left at random interval, user is stationary and will jump (skip) over obstacles as they appear by pressing the space bar. Player can win the game by playing for 120 seconds without colliding with an obstacle. After colliding with an obstacle, the game is lost.


## User Stories
**As a player, I want to be able to:**
- start the game by pressing a button
- use the space bar to play the game
- see a countdown timer to when the game ends
- see the status of the game when it ends
- see a status message when the game ends
- see a status message when I collide with obstacle
- play, pause and end the game by clicking a button
- reset the game after it ends

## Wireframes / Screenshots

![Wireframe_1](https://i.imgur.com/LACLp7T.png)

![Wireframe_2](https://i.imgur.com/DIXIiB3.png)


## Plan
- I plan to use html canvas to build the game.
- For obstacles, I will use a class to create a new obstacle with a randomizer for when they appear. I will use setInterval to space out obstacles and also the speed at which they move in and out of frame
- I will use setTimeOut to countdown the game until a win or lose condition is met
