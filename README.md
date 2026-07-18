# Chess Master

A fully featured web-based chess application with a beautiful modern design, advanced bot opponents, Board Editor, and Fairy Chess variants support!

## Features
- **Play Game**: Play standard chess against a human or various AI bots powered by custom Minimax algorithms and Stockfish.
- **Board Editor**: Set up custom board positions using a drag-and-drop editor. Validate positions instantly.
- **Fairy Variants**: Play with custom fairy chess pieces like Chancellor, Dragon, Zebra, and Amazon with customized starting positions.
- **Themes**: Multiple gorgeous board themes (Walnut, Green, Blue, Purple) and piece themes (Standard, Neo, Wood, Glass, Minimal).
- **Responsive Design**: Beautiful CSS styling with glassy panels, smooth animations, and mobile responsiveness.

## Technology Stack
- Vanilla HTML / CSS / JavaScript
- [chess.js](https://github.com/jhlywa/chess.js) for move validation and logic (modified for Fairy pieces)
- Stockfish WASM for advanced AI opponent analysis

## How to Run
Run a local development server in the root directory:
```bash
npx serve .
```
Then open `http://localhost:3000/chess.html` in your browser.
