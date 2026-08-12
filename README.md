# 2048 Game

A browser-based implementation of the classic 2048 puzzle game.

The goal is to combine tiles with the same numbers until you reach the **2048 tile**.

## Live Preview

[Live Demo](https://inna-code10.github.io/2048-game/)

## Technologies Used

This project was built using the following technologies:

* **HTML5:** For structuring the game interface and page content.
* **SCSS (Sass):** For styling the game board, tiles, controls, and different tile states in a clean and maintainable way.
* **JavaScript (ES6+):** For implementing the game logic, tile movement, merging, score calculation, keyboard controls, win/lose states, and restart functionality.
* **ES Modules:** For organizing JavaScript code using `import` and `export`.
* **NPM:** For managing project dependencies and running development scripts.
* **Parcel:** For bundling and serving the project during development.
* **Gulp / Mate Scripts:** For running development, linting, building, and deployment commands provided by the project template.
* **Git:** For version control and tracking changes in the project.
* **GitHub:** For hosting the repository and deploying the project with GitHub Pages.

## Features

* Classic 4×4 game board
* Random generation of `2` and `4` tiles
* Keyboard controls using arrow keys
* Tile movement in four directions
* Automatic merging of matching tiles
* Score tracking
* Different styles for different tile values
* Win detection when the `2048` tile is reached
* Game over detection when no moves are available
* Start and restart functionality

## Getting Started

To run the project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/Inna-code10/2048-game.git
   ```

2. Navigate to the project folder:

   ```bash
   cd 2048-game
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm start
   ```

## How to Play

1. Click the **Start** button.
2. Use the arrow keys on your keyboard to move the tiles:

   * `↑` — move up
   * `↓` — move down
   * `←` — move left
   * `→` — move right
3. When two tiles with the same number collide, they merge into one.
4. Continue combining tiles and increasing your score.
5. Reach the **2048** tile to win the game.
6. If there are no empty cells and no possible moves, the game is over.
7. Use the **Restart** button to reset the game.
