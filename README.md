# astrododgegame

AstroDodge Game
AstroDodge is a simple yet fun game where you control a spaceman dodging incoming asteroids. Navigate through space and see how long you can survive!

Getting Started
These instructions will get you a copy of the game up and running on your local machine for development and testing purposes.

Prerequisites
Python 3
pip (Python package manager)
Setting Up a Virtual Environment
On macOS
Open Terminal.
Navigate to the directory where you want to create your project.
Run python3 -m venv spaceenv to create a virtual environment named spaceenv.
Activate the environment with source spaceenv/bin/activate.
Your command line should now show (spaceenv) indicating the virtual environment is active.
On Windows
Open Command Prompt.
Navigate to the directory where you want to create your project.
Run python -m venv spaceenv to create a virtual environment named spaceenv.
Activate the environment with spaceenv\Scripts\activate.bat.
Your command line should now show (spaceenv) indicating the virtual environment is active.
Installing Pygame
With your virtual environment active, install Pygame by running:

pip install pygame
Running the Game
Clone or download this game repository to your local machine.
Ensure your virtual environment is active.
Navigate to the directory containing the game files.
Run the game with python game.py (replace game.py with the actual game script name).
Pygame Methods Used
pygame.init(): Initializes all the pygame modules. Necessary for running any pygame application.

pygame.display.set_mode((width, height)): Creates a window or screen for display with the specified width and height.

pygame.display.set_caption("Title"): Sets the title of the display window.

pygame.image.load('image_path.png'): Loads an image from the file system.

pygame.transform.scale(image, (width, height)): Scales the image to the specified width and height.

image.get_size(): Returns the size of the image as a tuple (width, height).

pygame.time.Clock(): Creates an object to help track time.

pygame.event.get(): Gets events from the queue.

pygame.key.get_pressed(): Returns a sequence of boolean values representing the state of every key on the keyboard.

pygame.transform.flip(image, xbool, ybool): Flips the image horizontally and/or vertically.

pygame.Rect(x, y, width, height): Creates a rectangle with the specified parameters. Useful for collision detection.

rect.colliderect(rect2): Tests if two rectangles (rect and rect2) overlap.

screen.fill(color): Fills the entire screen with the given color.

screen.blit(source, dest): Draws a source image (or part of it) to the screen at the specified destination.

pygame.display.update(): Updates the full display Surface to the screen.

clock.tick(framerate): Limits the game's framerate to the specified value.

pygame.quit(): Uninitialize all pygame modules and closes the window.
