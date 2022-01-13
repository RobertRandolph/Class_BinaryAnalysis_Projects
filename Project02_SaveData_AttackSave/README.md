# COSC5010_01_Project_02

A program that allows a user to play as a hero and fight monsters.  
Contains source code and documents for design and analysis.

## Requirements

- C++ compiler
- A command prompt

## Installation 

- Just build and run the source files
- Note: This was made using Visual Studio 2019 Community

## Usage

- Run the program and a list of commands will show up
- Type in commands to interact with the game

# Added Notes
The bolk of the code is actually the system itself, and not the save/load and file tampering detection.

Not the most polished or well thought out code, but the system wasn't the goal.

The encryption/decryption method is XOR, which isn't good, but I went with something simple so that I could have something to work with (and if this was a real system it could easily be replaced)

Due to the nature of the project, I cared about file tampering, so I tried to make a basic measure against this.

The .char file is an example of how a file was saved