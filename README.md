# No Command Clock
A bunch of scripts used to create One Command Block creations for Minecraft 1.9 snapshots

# Usage
* Create a file with a list of commands to execute 20 times a second.
* Execute `./createcommands <FILE NAME> "<BLOCK> <DATA VALUE>" > <OUTPUT>`.
Replace "FILE NAME" with the name of the file and "BLOCK" and "DATA VALUE" with the specifics of the block used to create the box. "OUTPUT" is the name of the file to output the commands for the next stage.
* Execute `./generatecommand <FILE>`.
Replace "FILE" with "OUTPUT" from the last command. This script will print out a long command. Copy this command to the clipboard
* In Minecraft, place a Command Block, paste this command and set the Command Block to "Always Active". Upon exitting the GUI, a structure will spawn and the commands will immediately start.

# Supported features
* Uses Repeating Command Blocks added in 15w34a
* Works without internet connection or MCEdit

# Planned features
* "Remove Machine" sign with a click event
* Custom signs
* Prettier box
* Commands that are run only once

#Included examples
* `example_commands.txt` - Example list of commands
* `example_script.sh` - Small script to execute the required comments and generate a One Command Block creation from the commands in `example_commands.txt`
