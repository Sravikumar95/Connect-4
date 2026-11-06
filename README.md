# Connect 4

A browser-based implementation of the classic Connect 4 game, built with plain HTML, CSS, and JavaScript. No frameworks or external libraries — just a grid, gravity logic, and win detection written from scratch.

## How it works

The game is played on a 6-row by 7-column board. Two players take turns, red and yellow, clicking anywhere in a column to drop a piece. The piece falls to the lowest available slot in that column, similar to the physical game. The first player to line up four pieces in a row, horizontally, vertically, or diagonally, wins.

## Features

- Fully dynamic board generation, no hardcoded grid in the HTML
- Column-based piece dropping that mimics gravity
- Win detection in all four directions: horizontal, vertical, and both diagonals
- Simple, readable game state tracked in a 2D array

## Tech used

- HTML for structure
- CSS for board and piece styling
- JavaScript for game logic and DOM manipulation

## Project structure

```
Connect-4/
  index.html       Main page structure
  style.css        Board and piece styling
  script.js        Game logic
  assets/          Background image
```

## Running it locally

This project has no dependencies and no build step. Just open `index.html` in a browser, or use a local server such as the VS Code Live Server extension for a smoother experience.

## Known limitations

- There is currently no draw detection if the board fills up without a winner
- No restart button after a game ends, the page needs to be refreshed
- No indicator showing whose turn it is
- The winning four pieces are not visually highlighted on the board

## Possible improvements

- Add a "Play Again" button that resets the board without a page reload
- Detect and display a draw when the board is full
- Highlight the winning line once a player wins
- Add a turn indicator
- Make the board layout responsive for smaller screens

## Author

Built by Ravi as part of a web development.
