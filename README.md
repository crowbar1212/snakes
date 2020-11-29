This program actively draws a snake game in the command prompt window. 

In order to replicate this program, do the following: 
    -Install Visual Studio Code
    -Install Python and Github extensions
    -Sign-in and connect to an existing Github account and repository
    -Tutorial outlines how to implement program.
    -Curses library allows us to interact with the terminal via text input (basic TUI)
    -Curser is set to 0 to essentially remove it from the screen
    - "newwin" creates a new window for drawing our game
    -keypad sets our input parameters for moving the snake, with timeout setting how often to refresh our game
    -addch adds our food, with curses.ACS_PI allowing us to use the pi symbol as the representation of the food
    -Key_right gives a starting vector for the snake
    -if snake moves off-screen(touches terminal borders) or moves into itself, the program is terminated
    -a new snake is drawn when the snake eats food, increasing in size
    -when snake "eats" food, a new food is placed at a random position in the terminal window



    -issues met when importing curses library, and some irregularities in code/syntax appear to be unsolved, though code appears to be working when run directly through command prompt (not in VSCode terminal window). Copying code from github repository doesn't seem to have fixed the issue so it's likely an issue with VScode itself rather than the actual code. 
    -Another note for this code version is that if the size of the command promp window is adjusted to any degree, snake food will not be generated properly after the first piece is consumed. Something to improve in future edits.


Snapshot proof of code working: https://imgur.com/gallery/VjxOrBK

Helping sources: 
https://www.youtube.com/watch?v=rbasThWVb-c
https://github.com/engineer-man/youtube/tree/master/015
https://www.codegrepper.com/code-examples/delphi/upgrade+pip+vscode
https://w3schools.com/python