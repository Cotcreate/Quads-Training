# Quads Training

A browser version of the tile game Quads for practising against a computer opponent, or playing a friend on the same device. It's a single HTML file with no install or build step.

**Play it:** https://cotcreate.github.io/Quads-Training/

## How to play

1. Each player has 17 tiles in their colour plus one starting tile. Light's starting tile is the concentric squares and Dark's is the cross. Every side of a tile is either solid colour or stripes.
2. Light starts. Each player's first move is their starting tile, placed on one of the 16 inner squares. Starting tiles can't go on the edge of the board, and there must be at least one empty square between them (they can't touch, not even at the corners).
3. After that, place one tile per turn on an empty square next to a tile already on the board. Tiles can be turned to any rotation.
4. Every side that touches another tile must match it: stripes against stripes running the same way, or solid against the same solid colour.
5. If you can't place a tile on your turn, you lose.

**House rule:** tiles on the edge of the board don't need to match the border.

## Computer levels

| Level | Plays like |
| --- | --- |
| 1 Novice | Almost any legal tile. Good for learning the joins. |
| 2 Casual | Looks one move ahead and makes mistakes. |
| 3 Skilled | Checks your best reply before it plays. |
| 4 Expert | Searches several moves deep and blocks hard. |

You can change the level mid-game. Practice aids include a hint button (uses the Expert search), undo, markers for the squares your tile fits, and an overlay showing which empty squares only you, only your opponent, or either of you can still fill.

## Run it locally

Download `index.html` and open it in any modern browser.

## Credits

Fan-made practice version of Quads, the 1996 tile game designed by Kris Burm. Not affiliated with the designer or publisher.
