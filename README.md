# END OF THE WORLD

https://areymadhav.itch.io/end-of-the-world

This is a 3D endless car racing game built using Python, Pygame, and PyOpenGL. The objective of the game is to avoid obstacles and achieve the highest score possible.

## Game Features
- Main Menu
- Pause Menu
- Game Over Screen
- Endless Obstacles
- Score Tracking

## Installation

### Prerequisites

Make sure you have Python installed on your system. You can download Python from [python.org](https://www.python.org/).

### Required Libraries

Install the required libraries using pip:
```bash
pip install pygame PyOpenGL
```

## Running the Game

To run the game, execute the `main.py` script:
```bash
python main.py
```

## Controls

- **Arrow Keys:** Move the car left and right.
- **P:** Pause/Resume the game.
- **Enter:** Start the game from the main menu or return to the main menu from the game over screen.

## Packaging the Game with PyInstaller

You can use `pyinstaller` to package the game into a standalone executable.

### Step 1: Install PyInstaller

If you haven't already, install `pyinstaller` using pip:
```bash
pip install pyinstaller
```

### Step 2: Create the Executable

Navigate to the directory containing your `main.py` file and run the following command:
```bash
pyinstaller --onefile --windowed main.py
```

### Step 3: Locate the Executable

After running `pyinstaller`, you will find the executable in the `dist` directory inside your project folder.

### Step 4: Run the Executable

Navigate to the `dist` directory and run the executable to start the game.

## Troubleshooting

If you encounter any issues while running or packaging the game, ensure that you have installed all the required libraries and have the correct version of Python.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Pygame](https://www.pygame.org/)
- [PyOpenGL](http://pyopengl.sourceforge.net/)
