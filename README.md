# 2048 Game – Interactive Puzzle

An engaging, browser-based version of the classic 2048 puzzle game.
Players move numbered tiles on a 4×4 grid using keyboard arrows, merging equal numbers to reach the 2048 tile.
The game dynamically updates the grid, tracks scores, and provides a smooth and responsive gaming experience.

## 🚀 Live Demo
Experience the live website👉 [Play the Game](https://Oksigenka.github.io/2048-puzzle-game/)

## 🕹 How to Play
- Use Arrow keys (↑ ↓ ← →) to slide all tiles in the chosen direction.
- Merging rule: two tiles with the same value merge into one tile with double the number.
- Score: increases by the sum of all merged tiles per move.
- After every move, a new tile with a value of 2 (90% chance) or 4 (10% chance) appears in a random empty cell.
- The goal is to create a tile with the number 2048.

## ⚡ Getting Started
Follow these steps to set up and run the project locally.

### 1. Clone the repository
```
git clone https://github.com/<your-username>/apple-catalog.git
cd react-phone-catalog
```
### 2. Install dependencies:
```
npm install
# or
yarn install
```
### 3. Run the project locally:
```
npm start
# or
yarn start
```
---

## ✨ Game Features
- 4×4 Grid Gameplay – faithful recreation of the classic 2048 mechanics.
- Dynamic Movement & Merging – tiles slide and combine smoothly; merged tiles cannot merge twice in one move.
- Win & Game Over Detection – win message shows when a 2048 tile is formed; game over appears when no moves are possible.
- Score Tracking – running score increases with each merge; best score saved during the session.
- Start / Restart Functionality – the game hides the start message on first move and transforms the Start button into Restart to reset the board.
- Random Tile Generation – each move spawns a new 2 or 4 tile in a random empty cell.
- Responsive & Fast – works on desktop and mobile browsers.

## 🛠 Technologies Used
- HTML – semantic markup for the game grid and interface.
- CSS – responsive layout and smooth animations for tiles and UI.
- JavaScript – core game logic, keyboard input handling, score updates, win/lose checks, and restart functionality.

## 💡 About the Project
This project showcases:
- Interactive design and real-time game state management
- User input handling with keyboard events
- Modular, maintainable code structure

---

Enjoy the challenge of reaching 2048 and beyond!
