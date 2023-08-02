# text_game
This repository contains a simple and engaging text-based game built in Python. The player can control a character's movement, moving left or right and jumping, to navigate through the game world. The goal is to collect items, earning points and increasing the player's score.
Features
Intuitive keyboard controls for moving the character left, right, and jumping.
A point system for collecting items.
Increasing difficulty as the player progresses.
Display of the current score and high score on the screen.
Code Structure
main.py: The entry point of the game.
game.py: Contains the Game class which handles the game logic, including starting and ending the game, updating the score, moving the player, checking for collisions, and rendering the game screen.
player.py: Contains the Player class which represents the player in the game. It has methods for moving the player left, right, and jumping.
item.py: Contains the Item class which represents the items in the game. It has a method for getting the position of the item.
ascii_art_generator.py: Contains the AsciiArtGenerator class which generates ASCII art for game elements. It has a method for generating ASCII art based on a given symbol.
Running the Game
The game requires Python and Pygame to run. Once you've installed these, you can start the game by running the main.py script:

python main.py

Enjoy the game!

