# Chession

Guess the chess opening based on a position played by grandmasters.

## How to play

  A chess position from a famous opening is shown on the board.
  Type the name of the opening, or start typing to filter from 25 options.
  Depending on the difficulty mode you choose, you can either have 5 or 6 guesses. "Normal mode" is the easier mode while the "grandmaster" mode is the harder mode.
  Each wrong guess steps the board back one full move, revealing an earlier position as a hint. In "normal move" on the last guess you get a "double hint" meaning the board goes back 2 full moves (2 moves for white and 2 moves for black, so 4 total moves)
  Use the arrow buttons (or arrow keys) to navigate between hint positions you've unlocked. 
  This is currently intended for players who are more familar with chess, however I will add difficulty modes in the future.

## Play it here

https://stashm10.github.io/Chession

## How I Built it

Everything was coded with HTML, CSS, and JavaScript. This web-based game is not complicated, thus the code itself should not be complicated either. Additionally I used chess.js for move validation and the piece graphics came from Lichess, which is an offical platofrom to play chess. Unfortunately I used ai to create the difficulty image.
