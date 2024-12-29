# TREX-Jumping-Game
# Run T-Rex Run

A classic 2D game where you control a jumping T-Rex to avoid obstacles and survive as long as possible. This game uses OpenGL in C for rendering and includes dynamic day-night cycles and customizable gameplay.

## Features

- **Dynamic Gameplay**:
  - Control a jumping T-Rex to dodge moving cactus obstacles.
  - Jump height and timing are key to survival.
  
- **Day-Night Cycle**:
  - A dynamic background simulating day and night transitions.
  - Stars appear in the night sky.

- **Customizable Gameplay**:
  - Change T-Rex colors, terrain styles, and cactus speed via an in-game menu.
  - Toggle sun visibility, spin effects, and size.

- **Game Over Screen**:
  - Displays the final score when the T-Rex is hit.

## Controls

- **Game Actions**:
  - `W`, `w`, or `Spacebar`: Make the T-Rex jump.
  - `R` or `r`: Restart the game.
  - `S` or `s`: Start the game.
  - `ESC`: Quit the game.

- **Menu**:
  - Right-click to access the in-game menu for customization options.

## Installation and Execution

1. **Requirements**:
   - A C compiler with OpenGL and GLUT libraries installed.

2. **Compilation**:
   Compile the program using the following command:
   ```bash
   gcc -o trex_game CG_Code_Trex.cpp -lGL -lGLU -lglut

3. **Execution**:
    Run the compiled program:
    ```bash
    ./trex_game
