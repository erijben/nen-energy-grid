# Nen Energy Grid — Manual Web Game

A lightweight browser mini-game for the “Nen Energy Grid” challenge.

## Goal
Start at **top-left** and reach **bottom-right**.

## Rules
- You can move **only Right or Down**.
- Your Nen **accumulates** by **adding the value of each visited cell**.
- Your total must **strictly increase** at every step ⇒ you can only step into cells with value **> 0**.
- Cells with **≤ 0** are blocked.

## How to play (Mouse)
1. Paste a grid as a JSON 2D array in **Grid Input**.
2. Click **Load Grid**.
3. In the grid, **click one of the highlighted neighbor cells** (green outline) to move.
4. Keep clicking valid next cells until you reach the **BOSS** cell (bottom-right).

## Buttons
- **Load Grid**: Load the JSON grid.
- **Random Grid**: Generate a demo grid.
- **Restart**: Restart from START using the current grid.
- **Reset**: Clear the current session.

## Run locally
Open `index.html` in any modern browser (no install, no build).

## Tech
- Single file: `index.html`
- No dependencies
- Works offline
