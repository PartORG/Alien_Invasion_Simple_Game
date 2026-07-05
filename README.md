# Alien Invasion Simple Game - A Python Version of Space Invaders

A simple version of the classic Space Invaders game, implemented in Python. This project provides a basic framework for understanding and creating games using the Pygame library.

## Table of Contents
1. [Features](#features)
2. [How It Works](#how-it-works)
3. [Technology Stack](#technology-stack)
4. [Requirements](#requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Project Structure](#project-structure)

## Features
### Alien Invasion Game
- **What it does:** A classic Space Invaders game where the player controls a ship to shoot down alien invaders.
- **Why it exists:** To provide a simple, educational example of game development using Python and Pygame.
- **Why it is useful:** Ideal for beginners learning game development or those looking to understand basic Pygame concepts.

## How It Works
The game follows a typical Space Invaders workflow:
1. The player controls a ship at the bottom of the screen.
2. Aliens move across the top of the screen in rows, shooting bullets downwards.
3. The player must shoot down the aliens before they reach the bottom of the screen.

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python 3.8+ | Programming language for game logic and user interaction. |
| Pygame 2.0.1 | Library used for creating the game window, handling events, and rendering graphics. |

## Requirements
- **Python:** Version 3.8 or higher.
- **Pygame:** Version 2.0.1.

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/PartORG/Alien_Invasion_Simple_Game.git
   cd Alien_Invasion_Simple_Game
   ```

2. Install the required Python packages using pip:
   ```sh
   pip install pygame==2.0.1
   ```

## Usage
To run the game, execute the following command:

```sh
python alien_invasion.py
```

This will start the Alien Invasion game. Use the left and right arrow keys to move the ship, and press the spacebar to shoot bullets at the invaders.

## Project Structure

```
Alien_Invasion_Simple_Game/
├── .gitignore
├── README.md
├── alien.py
├── alien_invasion.py
├── bullet.py
├── button.py
├── game_stats.py
├── images/
│   ├── alien.bmp
│   └── ship.bmp
├── score_board.py
└── settings.py
```

- **alien.py:** Contains the logic for the alien objects.
- **alien_invasion.py:** The main entry point of the game, initializes and runs the game loop.
- **bullet.py:** Handles the bullet objects that the player shoots.
- **button.py:** Manages buttons in the game interface.
- **game_stats.py:** Keeps track of game statistics like score and level.
- **images/**: Contains image files used in the game.
- **score_board.py:** Displays the current score on the screen.
- **settings.py:** Stores settings for the game, such as dimensions and colors.

## Development
This project is a simple example and does not include advanced development features. Contributions are welcome to add more features or improve existing ones.

## License
The license for this project has not been detected. If you have any questions regarding licensing, please contact the repository owner.