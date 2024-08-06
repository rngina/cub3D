# cub3D
cub3D project from 42 School, inspired by the [Wolfenstein 3D game](http://users.atw.hu/wolf3d/).

## Overview
The goal was to create a dynamic view inside the maze based on the 2D map using [raycasting](https://lodev.org/cgtutor/raycasting.html) and the small graphics library [MiniLibX](https://github.com/42Paris/minilibx-linux).

![Inside the maze](/screen.png)

## Controls

- **Look Around**: Use the left and right arrow keys to rotate your view.
- **Move**: Use W, A, S, and D keys to move forward, left, backward ans right.
- **Quit**: Press the ESC key or click the cross on the window frame to exit the program.

![cub3d gif](/cub3d.gif)

## Compile and run

Clone the repository
```shell
git clone https://github.com/rngina/cub3D.git
```

Include [MiniLibX](https://github.com/42Paris/minilibx-linux) to the root of the project and then run
```shell
make
```

Execute the program
```shell
./cub3d <path/to/map.cub>

