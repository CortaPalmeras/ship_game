
# Project Overview

This project features an simple open-ended game where the player navigates a ship through a scene containing randomly generated donut shapes.

## Game Mechanics

The ship can be controlled using the "w" and "s" keys for forward and backward movement, respectively. Horizontal rotation is achieved with the "a" and "d" keys, while vertical rotation is controlled by the mouse.

By pressin "r", the ship can lay down control points to create a smooth trajectory. By pressing the "1" key, the ship will automatically follow this trajectory.

## Additional Features

Additionally, the ship can execute a spin animation at any time during the game by pressing the "p" key.

## Dependencies and Execution

This application depends on three Python libraries, namely Pyglet, PyOpenGL, and NumPy. To install these dependencies, use pip:

```bash
pip install pyglet pyopengl numpy
```

Once the dependencies are installed, the program can be executed by running the following command in the terminal:

```bash
python ship.py
```