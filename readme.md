# Snake-Labs Game

## Introduction

The **Advanced Snake Game** is a modern take on the classic snake game, featuring customizable grid sizes, obstacle generation, and a unique pathfinding algorithm. This interactive simulation offers a more strategic experience by allowing players to set start and end points and dynamically interact with the environment.

Check out the demo [here](https://quantumwings.github.io/Snake-Labs/).

## Main Functions

- Create a customizable grid of size `n x n`.
- Set start and end points within the grid.
- Automatically generate obstacles and find a path between start and end points.
- Visualize the pathfinding algorithm in action with real-time animations.
- Reset the grid and game settings with a click of a button.

## Installation and Setup Guide

### Environmental Requirements
- A modern web browser that supports HTML5 and JavaScript (e.g., Chrome, Firefox, Safari).
- A web server for local hosting (optional, but recommended for better performance).

### How to Use
1. Download the project files to a local directory.
2. Use a web server to host the `index.html` file, or simply open the file directly in your browser.

## Instructions for Use

### Operation Steps
1. After opening the application, you will see the main game interface with a control panel at the top.
2. Adjust the grid size by entering a value between 5 and 20 and clicking "Create Grid".
3. Click on any cell to set it as the starting point (marked in green).
4. Click on a different cell to set it as the ending point (marked in red).
5. Click the "Start Game" button to begin the simulation:
   - The game will automatically generate obstacles.
   - The pathfinding algorithm will find a path from the start to the end point.
   - If a path is found, it will be highlighted and animated.
6. Click "Reset Game" to clear the grid and start over.
7. To view the game instructions, click the "Game Instructions" button.

### Example
- Set grid size to 10.
- Click to choose a starting point (green) and an ending point (red).
- Start the game to see the pathfinding algorithm in action.

## Project Structure
- `index.html`: Main HTML file that sets up the game structure and interface.
- `style.css`: Contains all the styling for the game elements.
- `script.js`: JavaScript file that handles game logic, including grid creation, user interactions, and pathfinding algorithm.
- `images/`: Directory containing any visual assets used in the game.

## Contribution Guidelines
If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to your local environment.
2. Create a new branch for your feature or bug fix (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push the changes to your branch (`git push origin feature-branch`).
5. Submit a Pull Request for review.

## Authorization Information
This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Contact Information
If you have any questions or suggestions, please contact the project maintainer: quantumwingslab@gmail.com

## Other Information
This game is designed for educational and entertainment purposes, showcasing basic concepts in game development and algorithm visualization. Feel free to use, modify, and enhance it for personal and learning use.
