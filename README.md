# 2D Car Arcade Game

A fun and engaging 2D car racing game built using OpenGL and C++. Navigate through traffic, avoid obstacles, and try to achieve the highest score!

## Features

- 🚗 Three-lane racing gameplay
- 🎮 Multiple player profiles support
- 🎯 Various obstacles to avoid (cars, bushes, rocks, traffic cones)
- 💖 Lives system with heart indicators
- 🎵 Background music and sound effects
- 🏆 High score tracking
- 🎨 Beautiful graphics with sprite-based rendering

## Prerequisites

- C++ compiler with C++11 support
- OpenGL
- GLUT (OpenGL Utility Toolkit)
- SDL2 and SDL2_mixer for audio
- stb_image.h for texture loading

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/2D-Car-Arcade.git
cd 2D-Car-Arcade
```

2. Install dependencies:
   - For macOS:
   ```bash
   brew install sdl2 sdl2_mixer
   ```
   - For Ubuntu/Debian:
   ```bash
   sudo apt-get install libsdl2-dev libsdl2-mixer-dev
   ```

3. Compile the game:
```bash
g++ car_game.cpp -o car_game -framework OpenGL -framework GLUT -lSDL2 -lSDL2_mixer
```

## How to Play

1. Launch the game
2. Select an existing player profile or register a new one
3. Use the following controls:
   - Left Arrow: Move car to the left lane
   - Right Arrow: Move car to the right lane
   - ESC: Pause game
   - Mouse: Navigate menus

## Game Rules

- Start with 3 lives
- Avoid collisions with obstacles
- Score points by successfully navigating through traffic
- Game ends when all lives are lost

## Project Structure

- `car_game.cpp`: Main game source code
- Various `.png` files: Game assets (sprites and textures)
- `sound.mp3`: Background music
- `stb_image.h`: Image loading library

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenGL community for graphics support
- SDL2 team for audio implementation
- stb_image.h for texture loading functionality 