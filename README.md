# Simon-Says-Game

A web-based "Simon Says" game built using HTML, CSS, and JavaScript.

## Overview

This project is a simple implementation of the classic "Simon Says" game, where users must repeat a sequence of colors and sounds as dictated by the game.

### HTML Code

The HTML file (`index.html`) provides the basic structure of the game interface. It includes the title, a message to start the game, and four colored buttons representing the game elements.

### CSS Styling

The CSS file (`SimonGame.css`) styles the buttons and container to create an aesthetically pleasing interface. It includes different colors and flash effects for button interaction.

### JavaScript Logic

The JavaScript file (`SimonGame.js`) contains the game logic. It handles user interactions, generates the sequence of colors, manages user input, and keeps track of the game's state.

## How it Works

1. **Starting the Game**:
    - Users start the game by pressing any key, as indicated in the message on the screen.
2. **Gameplay**:
    - The game generates a sequence of colors. Each color represents a button.
    - The sequence plays through a flash animation on the buttons in a specific order.
    - Users must then replicate the sequence by clicking the buttons in the same order.
3. **Scoring and Progress**:
    - With each correct sequence, the game progresses to the next level, increasing in difficulty.
    - The user's level is displayed on the screen as they progress through the game.
4. **Game Over**:
    - If the user fails to replicate the correct sequence, the game ends, and the user's score is displayed.
    - Users can restart the game by pressing any key after the game over.

## Running the Game

1. **Clone the Repository**: Clone or download the repository to your local machine.
2. **Open `index.html`**: Open the `index.html` file in a web browser.
3. **Start Playing**: Press any key to initiate the game.

## Notes

- The game uses simple button clicks and keypress events for user interaction.
- The background changes color briefly in case of a game over scenario.

Feel free to explore the game, customize the colors or styles, or add more features to enhance the gameplay!
