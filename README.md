# Simons-Game
Simone game using jQuery

## Overview

The Simon Game is a classic memory game where players must remember and repeat sequences of colors. This project implements the Simon Game using HTML, CSS, and JavaScript.

## Project Files

- **index.html**: The main HTML file that structures the game interface.
- **styles.css**: The CSS file that styles the game interface.
- **game.js**: The JavaScript file that contains the game logic.

## Setup

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd simon-game
    ```

2. **Open `index.html`** in your web browser to start the game.

## How to Play

1. Press any key to start the game.
2. Watch the sequence of colors that light up.
3. Repeat the sequence by clicking the corresponding colored buttons.
4. If you correctly follow the sequence, a new color will be added to the sequence.
5. The game ends if you click the wrong button.

## Files Description

### index.html

This file contains the structure of the game interface. It includes the following elements:

- A title that displays the current game level or game over message.
- A container with four colored buttons (red, blue, green, yellow) representing the game pads.

### styles.css

This file contains the styles for the game interface. It includes styles for:

- The body, setting the background color and text alignment.
- The title, defining font family, size, margin, and color.
- The container and buttons, setting dimensions, colors, and border properties.
- Classes for game-over and pressed button states.

### game.js

This file contains the game logic, including functions to:

- Handle user input via key presses and button clicks.
- Generate and display the game sequence.
- Check the user's input against the game sequence.
- Play sounds and animate button presses.
- Handle game over and restart scenarios.
