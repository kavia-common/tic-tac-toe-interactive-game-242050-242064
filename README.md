# Tic-Tac-Toe Interactive Game (React)

## Overview

This repository contains a React frontend application intended to be a simple interactive tic-tac-toe game. The React app lives under `tic_tac_toe_frontend/` and is built with Create React App (`react-scripts`).

## Features

At the time of writing, the frontend code in `src/App.js` renders the default React template UI plus a working light/dark theme toggle. The tic-tac-toe game UI and game logic described in the work item are not yet implemented in the current source code.

## Run locally (preview on port 3000)

The frontend runs on port 3000 by default.

1. Install dependencies:

   ```bash
   cd tic_tac_toe_frontend
   npm install
   ```

2. Start the development server:

   ```bash
   npm start
   ```

3. Open the app:

   http://localhost:3000

## Basic project structure

The important folders/files in this repository are:

- `tic_tac_toe_frontend/`: React application (Create React App)
  - `package.json`: dependencies and scripts (`start`, `build`, `test`)
  - `public/`: static assets and HTML template
  - `src/`: application source code
    - `index.js`: React entry point
    - `App.js`: main application component
    - `App.css`, `index.css`: styling
    - `App.test.js`, `setupTests.js`: test scaffolding

## Notes

If you are looking for the tic-tac-toe gameplay (3x3 grid, turn indicator, win/draw detection, and new game button), it will need to be added to `tic_tac_toe_frontend/src/App.js` (and supporting components/styles) because the current app is still a template-style UI with theme toggling.
