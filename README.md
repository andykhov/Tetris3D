# Tetris3D by Andy Khov

Tetris3D rendered with OpenGL and written in C++

![screenshot](./res/screenshot.jpeg "screenshot")

## Directions
* Use arrow keys to move the tetris block
* Spacebar to immediately drop the tetris block
* Z to rotate
* X to hold
* ESC to quit game

## Steps to run this app
1. create a build folder and move into build folder
2. run "cmake .."
3. run "make -j4"
4. run "./Tetris3D.out"

## Dependencies (Or just dependency haha)
* OpenGL
 * GLEW
 * GLFW
 * GLM

* This project was done as my final project for Cal Poly's Intro to Graphics course
* Thank you to Christian Eckhardt for being a wonderful professor!
* Most code was given as a base code. (except Main.cpp, Tetromino.cpp, Tetromino.h, Board.cpp, Board.h)
 * Base code is used to provide window, shader, and object management
 * Game mechanics are in Board.cpp and Tetromino.cpp
