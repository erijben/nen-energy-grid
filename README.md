# Nen Energy Grid

A tiny, submission-ready web mini-game + solver for the “Nen Energy Grid” challenge.

## What it does
- Renders a grid of energy values (Nen).
- Hunter starts at **top-left** and must reach **bottom-right**.
- Moves allowed: **Right** or **Down**.
- Each move “eats” the cell value and adds it to total Nen.
- Rule enforced: total Nen must **strictly increase** at every step ⇒ you may only step into cells with value **> 0**.
- Finds a valid path (if it exists) and **animates** the hunter cell-by-cell.

## Run locally
Just open `index.html` in your browser.

## Use
1. Paste a grid in JSON format (2D array), example:
   ```json
   [[5,3,2],[4,1,2],[1,1,9]]
Click Check & Play.

If a path exists, the hunter will animate along it and the total Nen will update.

##Random demo
Click Random Grid to generate a new grid and instantly play.

Tech

Single file: index.html

No dependencies, no build step, works offline.
