# city-puzzle-game-
 A simple browser-based city-building puzzle game.   Drag and drop tiles onto a shared grid, score points by matching neighbours and connecting roads, and try to beat the AI over 15 rounds.


City Puzzle – User vs AI

A simple browser-based city-building puzzle game.  
Drag and drop tiles onto a shared grid, score points by matching neighbours and connecting roads, and try to beat the AI over 15 rounds.

---
How to Play

1. Open `city-puzzle.html` in any modern browser (Chrome, Firefox, Edge, Safari).
2. Choose a difficulty:
   - **Easy** – 6×6 grid, weaker AI
   - **Normal** – 8×8 grid, balanced AI
   - **Hard** – 10×10 grid, stronger AI
3. Click **New Game**.
4. Drag a tile from your hand and drop it on an empty cell.
5. The AI automatically plays after your move.
6. After 15 full rounds the higher score wins.

---

Game Rules

- The game lasts exactly **15 rounds**.
- One round = your placement + the AI’s placement.
- You always start first.
- Tiles can only be placed on empty cells.
- After each of your moves the AI responds automatically.
- When the 15th round finishes, the game ends and the winner is declared.

---

Scoring

| Action                        | Points      |
|-------------------------------|-------------|
| Base placement                | +1          |
| Each matching neighbour       | +3          |
| Road connected to another road| +1 per link |
| Special tile (🎁)             | +3 + matches|
| Cluster bonus (2+ matches)    | +2          |

Matching the same type of tile next to each other is the main way to score well.  
Roads reward being linked together. Special tiles give a bigger bonus.

---

## Tile Types

| Tile          | Emoji | Colour     | Notes                     |
|---------------|-------|------------|---------------------------|
| Residential   | 🏠    | Green      | Common                    |
| Commercial    | 🏢    | Blue       | Common                    |
| Industrial    | 🏭    | Orange     | Common                    |
| Park          | 🌳    | Light green| Common                    |
| Road          | 🛣️    | Grey       | Scores extra when linked  |
| Special       | 🎁    | Purple     | Rarer, higher score       |

---
Difficulty Levels

| Level  | Grid  | Hand size | AI strength | Description                     |
|--------|-------|-----------|-------------|---------------------------------|
| Easy   | 6×6   | 4 tiles   | Low         | Good for learning the scoring   |
| Normal | 8×8   | 4 tiles   | Medium      | Balanced challenge              |
| Hard   | 10×10 | 3 tiles   | High        | Fewer tiles, smarter opponent   |

---

Controls
Drag & drop– pick a tile from your hand and drop it on an empty cell.
- New Game** – restart at any time with the currently selected difficulty.
- Difficulty can be changed before starting a new game.

---
 Tips

- Try to build clusters of the same tile type.
- Connect roads whenever possible.
- Special tiles are valuable – place them next to matching neighbours for maximum points.
- On Hard the AI evaluates more possible moves, so plan ahead.

---

Technical Notes

- Single HTML file, no external libraries or internet required.
- Works offline once downloaded.
- Pure HTML + CSS + JavaScript.
- Compatible with desktop and most mobile browsers (drag & drop works best with a mouse or trackpad).

---

Enjoy the game!
