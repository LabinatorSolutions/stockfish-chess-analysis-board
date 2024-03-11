# BoldChess Web App

![GUI Type](https://img.shields.io/badge/Type-Web_GUI-orange)
![JavaScript](https://img.shields.io/badge/Language-JavaScript-yellow)
![Node.js](https://img.shields.io/badge/Node.js-Yes-026e00)
![Express.js](https://img.shields.io/badge/Express.js-Yes-ebd81c)
![Stockfish Chess Engine](https://img.shields.io/badge/Stockfish_Chess_Engine-Yes-43AC6A)
![Mobile Support](https://img.shields.io/badge/Touch_Based_Device_Support-Yes-purple)
![Known Bugs](https://img.shields.io/badge/Known_Bugs-0-green)

The official chess web-based app of the [BoldChess.com](https://boldchess.com/) website.
It is a responsive web GUI for the Stockfish chess engine with analysis, evaluation, and graphs. It also comes with Leela Chess Zero (LCZero) neural network evaluation.

---

## Mission

Our mission from this project is to develop a modern responsive free and open source web-based chess app powered by the Stockfish chess engine.

---

## Live Demo On BoldChess.com

[https://app.boldchess.com/](https://app.boldchess.com/)

---

## Features

- Ability to load your chess position or game using FEN, PGN, or a move list.
- Ability to set up your pieces manually in edit mode.
- Ability to browse game history with arrows or mouse wheel.
- Ability to list all legal moves and show them on the chessboard.
- Ability to analyze positions and all legal moves with the javascript version of the Stockfish chess engine.
- Ability to display an evaluation graph while visualizing blunders in different colors.
- Ability to open a position or game in a new window via a given URL.
- Ability to play against the computer (Stockfish Chess Engine) and set its difficulty level.
- Ability to see an evaluation by the Leela Chess Zero (LCZero) neural network.
- Ability to detect an opening category or ECO code.
- Ability to choose the styling of the chessboard.
- Ability to print arrows or mark squares on the chessboard.
- Relevant squares on the chessboard are visualized according to the static evaluation terms of the Stockfish chess engine.
- Dark interface with pitch black background that is battery-saving for OLED screens and highly intuitive.
- Support for PCs, tablets, smartphones, and touch devices.

---

## Available Windows

- Chessboard
- List of Moves
- Game History
- Graph
- Chess Openings
- Static Evaluation
- Edit Board

---

## GUI Instructions

- To open your FEN or PGN, copy your FEN or PGN to clipboard and paste it in the input box above the chessboard.
- To browse the game, use the mouse wheel on the chessboard or the arrow buttons.
- To open or hide windows, click on the small icons found at the top of the GUI.
- To play against the engine or set its difficulty level, click on the hamburger menu.
- To change the styling of the board, flip the board, or open it in a new window, click on the hamburger menu. 

---

## Installation

1. **Prerequisites**:
   - Ensure Node.js is installed on your machine. If not, download and install it from [Node.js official website](https://nodejs.org/).

2. **Repository Setup**:
   - Clone the repository to your local machine.
   - Navigate to the project directory.

3. **Dependency Installation**:
   - Install the project dependencies by running:
     ```bash
     npm install
     ```

4. **Local Server**:
   - Start the local development server:
     ```bash
     npm run start
     ```
   - Access the application by opening `http://localhost:3000` in a web browser.

---

## List Of Important Improvements & Issues

[https://github.com/LabinatorSolutions/boldchess-web-app/issues](https://github.com/LabinatorSolutions/boldchess-web-app/issues)

---

## Contribution

We welcome all developers to contribute to this repository by adding features or fixing bugs. The source codes will always be free and open source.

**List Of Current Contributors:**

[https://github.com/LabinatorSolutions/boldchess-web-app/graphs/contributors](https://github.com/LabinatorSolutions/boldchess-web-app/graphs/contributors)

---

## License

GNU GPLv3: [https://www.gnu.org/licenses/gpl-3.0-standalone.html](https://www.gnu.org/licenses/gpl-3.0-standalone.html)

---

## Credits

- [Stockfish](https://github.com/mcostalba/Stockfish)
- [Stockfish.js (nmrugg)](https://github.com/nmrugg/stockfish.js)
- [Stockfish.js (niklasf)](https://github.com/niklasf/stockfish.js)
- [LeelaChessZero](https://github.com/LeelaChessZero)
- [LC0-JS](https://github.com/frpays/lc0-js)
- [TensorFlow](https://github.com/tensorflow/tensorflow)
- [PeshkaChess](https://github.com/hxim/PeshkaChess)
- [BoldChess](https://boldchess.com/)
- [Labinator](https://labinator.com/)
