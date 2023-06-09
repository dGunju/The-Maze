# The-Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world.

The Maze was written in C using SDL2 library. Deveploment was performed using Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4

### About SDL2 

Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is used by video playback software, emulators, and popular games including Valve's award winning catalog and many Humble Bundle games.

## Repository
```sh
$ https://github.com/dGunju/The-Maze
```

## Installation 
```sh
$ git clone https://github.com/dGunju/The-Maze.git
```
## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```

## Flowchart
![The Maze Flow Chart](https://i.imgur.com/nE5Mgpi.jpg)

## Demo
[![The Maze Demo](https://i.imgur.com/5Ss7s1S.png)](https://drive.google.com/file/d/1-Uu7Vwc7f9s1TGd9vAw6VX2--t62jMFi/view?usp=sharing)