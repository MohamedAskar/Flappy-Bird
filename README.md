# Flappy Bird with Python (PyOpenGL)


In this project we recreate the famous game [Flappy Bird](https://en.wikipedia.org/wiki/Flappy_Bird) usnig OpenGL libraries and Python programming language.

## Introduction

With the help of [BEKA Engine](https://github.com/MwEg777/BEKA-Engine). We were able to recreate our version of Flappy Bird with some tweaks added to make the game more enjoyable.

**Note: PyGame is required to load images and sounds.**

## Code:
Our code consist of three main classes:
  - [`GameObject`](https://github.com/MohamedAskar/Flappy-Bird/blob/1d7da5b5711e48549ee51b245efbff96bc965b1e/main.py#L11) class is used for converting any thing into object we can get its position and apply transformation on the object.

  - [`FlappyImages`](https://github.com/MohamedAskar/Flappy-Bird/blob/1d7da5b5711e48549ee51b245efbff96bc965b1e/main.py#L45) class is used for loading game images into memory for later use.
  
  - [`ImageRenderer`](https://github.com/MohamedAskar/Flappy-Bird/blob/1d7da5b5711e48549ee51b245efbff96bc965b1e/main.py#L73) class is used for rendering the loaded images to the screen given the selected image coordinates.
  
  
We have also implementing other functions to handle everything that could happen in the game such as rendering score, pipes, credits and sound effects, handling bird movement, testing collision, and other helper functions also.

## Gameplay:

![Gameplay](Gameplay.gif)

## Contributions:
This project was a collage teamwork project and all team members are listed in the credits section in the end of the game.
