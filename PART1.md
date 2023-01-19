# Part 1

## Video Demo

Please provide the YouTube link to your [Video Demo](https://youtube.com).

## Minimum Requirements

### Completed

List all the features completed.

1. Cool Feature #1
2. Cool Feature #2
3. *add more*

### To Do

List all the features not yet done. Remove this section if there is no incomplete requirements.

1. Randomly generate game board default settings (columns and rows must be in odd number values)
    * Allows user to change default settings and input custom values (validation for odd number inputs only for game board dimensions)
    * Randomize alien and zombie attributes
           * Alien  - Life, Attack (0)
           * Zombie - Life, Attack, Range (less than game board dimensions)

2. Define object properties and behaviours
    *  Arrows ( ^ v < > ) - changes direction of alien, add 20 attack to alien
    *  Health ( h )       - adds 20 health to alien if current health is less than max health
    *  Pod ( p )          - inflicts 10 damage to the nearest zombie
    *  Rock ( r )         - stops alien from moving, reveals new object underneath it when hit
    *  Trail ( . )        - left behind as alien moves, reset to random object after alien's turn ends

3. Program player-input commands as functions 
    * up    - alien to move up
    * down  - alien to move down
    * left  - alien to move left
    * right - alien to move right
    * arrow - changes the direction of existing arrows on the board, ask for user to input row and column of the arrow, validation
    * help  - displays all available game commands and its functions
    * save  - saves the game
    * load  - loads game file, asks user whether current game should be saved
    * quit  - quits the game, asks user for confirmation

4. Display active turn of which character and game status message during turns

5. Load and save game function
    * save  - saves the game
    * load  - loads game file, asks user whether current game should be saved
    * quit  - quits the game, asks user for confirmation

## Additional Features

Describe the additional features that has been implemented.

## Contributions

List down the contribution of each group members.

For example:

### Ang Hui Yee

1. Randomly generate game board
2. *add more*

### Cheryl Gwee En Xin

1. Zombie movement and attack behaviour.
2. *add more*

### Yap Jack

1. Implement all game objects.
2. *add more*

## Problems Encountered & Solutions

Describe the problems encountered and provide the solutions / plan for the solutions.
