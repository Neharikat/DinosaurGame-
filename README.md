
# Dino Game Setup with Thonny

This repository contains a simple **Dino Game** built using **Python** and **Pygame**. The game is a clone of the popular Google Chrome Dino game, where you control a dinosaur to avoid obstacles such as cacti and birds.

## Prerequisites

Before running the game, ensure you have the following installed:

- **Thonny IDE**
- **Python 3.6+**
- **Pygame library**

## Installation Steps

### 1. Install Thonny IDE

Thonny is a beginner-friendly Python IDE. To install Thonny:

- **Windows**:
  1. Download Thonny from the official website: [https://thonny.org/](https://thonny.org/)
  2. Run the installer and follow the installation instructions.

- **macOS**:
  1. Download Thonny from [https://thonny.org/](https://thonny.org/)
  2. Open the `.dmg` file and drag Thonny into the Applications folder.

- **Linux**:
  1. Install Thonny using the following command:
     ```bash
     sudo apt-get install thonny
     ```

### 2. Install Python

Ensure Python 3.6+ is installed on your system.

- **Windows/macOS**: Python is usually bundled with Thonny. If not, you can install it from [python.org](https://www.python.org/downloads/).
- **Linux**:
  Install Python 3 with:
  ```bash
  sudo apt-get install python3
  ```

### 3. Install Pygame Library

To install Pygame, open **Thonny**, and follow these steps:

1. Go to **Tools > Manage Packages**.
2. Search for `pygame` and click **Install**.

Alternatively, you can install it using the command line:
```bash
pip install pygame
```

### 4. Download or Clone the Project

Clone or download the project repository to your local machine.

```bash
git clone <repository_url>
```

Ensure that the following directory structure exists in the project:

```
dino_game/
│
├── Assets/
│   ├── Dino/
│   │   ├── DinoRun1.png
│   │   ├── DinoRun2.png
│   │   ├── DinoJump.png
│   │   ├── DinoDuck1.png
│   │   └── DinoDuck2.png
│   ├── Cactus/
│   │   ├── SmallCactus1.png
│   │   ├── SmallCactus2.png
│   │   ├── SmallCactus3.png
│   │   ├── LargeCactus1.png
│   │   ├── LargeCactus2.png
│   │   └── LargeCactus3.png
│   ├── Bird/
│   │   ├── Bird1.png
│   │   └── Bird2.png
│   └── Other/
│       ├── Cloud.png
│       └── Track.png
│
└── main.py
```

### 5. Running the Game

Once you've installed Thonny, Python, and Pygame, and downloaded the project, follow these steps to run the game:

1. Open **Thonny**.
2. Open the `main.py` file (the Python script containing the Dino game code).
3. Press **Run** (F5) in Thonny to start the game.

### Controls:
- **Up Arrow**: Makes the Dino jump.
- **Down Arrow**: Makes the Dino duck.

The game will start in a window where you control the dinosaur to avoid obstacles that appear on the screen. The goal is to avoid hitting the obstacles (cacti and birds) and achieve the highest score.

---

## Code Overview

The game consists of the following components:

1. **Dino Class**: Handles the dinosaur’s movement (running, jumping, ducking).
2. **Cloud Class**: Controls the movement of clouds in the background.
3. **Obstacle Class** and **Subclasses**: Manages different types of obstacles such as small cacti, large cacti, and birds.
4. **Main Game Loop**: The `main_game()` function runs the game, handles user input, and updates the game state.

### Scoring:
- The game keeps track of the score, which increases over time.
- As the score increases, the speed of the game increases, making it more challenging to avoid obstacles.

---

## Troubleshooting

- **Game doesn't start**: Make sure Pygame is installed properly. You can verify this by running the following code in Thonny's shell:
  ```python
  import pygame
  pygame.init()
  ```
  If there are no errors, Pygame is installed correctly.

- **Missing assets**: Ensure that the image files are correctly placed in the `Assets` folder as specified.

---

Enjoy playing and feel free to modify the game to add your own features or improvements!

--- 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

---

This `README.md` file provides detailed instructions on how to install and run the Dino game using Thonny, along with some troubleshooting tips and an overview of the game’s code. Feel free to modify it as per your project's specifics!
