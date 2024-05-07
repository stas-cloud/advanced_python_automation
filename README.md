# advanced_python_automation
Python automation script. sys, os, subprocesses, search, copy, move, replace...

# Assumptions:

- data directory contains many files and directories
- you are only interested in the games contaiend in this directory
- each game is stored in a directory that contains the word "game"
- each game directory contains a single .go file that must be compiled before it can be run


# Project Steps/Requirements:

- Find all game directories from /data
- Create a new /games directory 
- Copy and remove the "game" suffix of all games into the /games directory
- Create a .json file with the information about the games
- Compile all of the game code

# How to run:

python get_game_data.py <source folder name> <destinatio folder name>

example: python get_game_data.py data target