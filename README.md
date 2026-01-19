# Turtle-Crossing-game
This project is a Python arcade-style game inspired by the classic Frogger, built using the turtle graphics module. The player controls a turtle that must cross a busy road while avoiding moving cars. Each successful crossing increases the difficulty level.

How the Game Works

The player uses the Up Arrow key to move the turtle upward which moves the car

If the turtle collides with a car, the game ends.

Each time the turtle reaches the top of the screen safely:

The level increases.

Cars move faster.

The turtle resets to the starting position.

Game Logic Overview

Player: Handles turtle movement and position.

CarManager: Spawns cars and controls their speed and movement.

Scoreboard: Displays the current level and game over message.

The game loop updates the screen, moves cars, checks for collisions, and tracks level progression.

Technologies Used

Python 3

turtle module

time module

Object-Oriented Programming (OOP)
