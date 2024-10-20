# Saul Knight

*** IMPORTANT: you must install the packages from requirements.txt before running the game.py file! File
game.exe (alternative startup) can be correctly launched only via terminal (command line).***

## Gameplay

Walk on WASD or with the arrows. Point weapons and shoot with the mouse (LKM).
Interact with objects with 'E'. Pause during gameplay with SPACE.

## Project structure

There are two ways to run: game.exe or game.py. **Game.exe can only be run via terminal!
Game.py requires the python interpreter and the packages specified in requirements.txt .

The file to run is game.py. Auxiliary classes and functions are scattered one by one or several by
files with corresponding names.

#### Read more:

+ game.py - imports and runs main_menu. Contains functions for level generation, sprite update,
level loop and a function to terminate everything.
+ mainmenu.py - contains one function with the main main main menu loop, through which level selection, etc. is done.
+ button_main - contains a function that shows the pause menu during the level.
+ button_d - contains a class describing the button used in the pause menu.
+ constants.py - contains basic game constants, sprite groups, etc.
+ my_sprites.py - game sprites (player, enemies and their base class).
+ tiles_camera.py - tiles and camera.
+ bullet.py - bullet, which shoots the player and villains.
+ data_loader.py - functions for loading images and level from text files.
