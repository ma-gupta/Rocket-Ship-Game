# Rocket Ship Game

Uses C++ code that is rendered using OpenGL and the GLFW framework.
Creates an interactive game space where the user can use keyboard and mouse controls to move around a rocket ship to collect diamonds that power up the ship (ship will grow). The game updates and displays score in real time and will be won once 3 diamonds are collected. 
This program utilized matrix transformations for smooth ship movement and textures that interact with the shader pipeline.

## Usage and Keyboard Controls

Diamonds can be picked up when the tip of the ship passes over the diamond or the tip of the ship is rotated into the diamond.

When a diamond is picked up the ship will grow.

Player wins when all the diamonds have been picked up and the score reaches 3.

Ship Controls:
-------------
Left Mouse Button - rotates ship in direction of click

W Key - moves ship forward

S Key - moves ship backward

Game Controls:
-------------
F5 Key - restarts/resets game

## Running and Compiling
Running and Compliing of this program will require several third party GLFW libraries (argh- 1.3.1, fmt-7.0.3, glew-2.1.0, glfw-3.3.2, glm-0.9.9.7, imgui-1.78, stb-2.26, vivd-2.2.1)
