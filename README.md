# Simon Says Game

## Overview
Simon Says is a memory game where the player must remember and repeat an increasing sequence of colors. Each correct repetition advances the level by adding a new color to the sequence. The game ends on the first wrong input.

## How It Works
- The game generates a random color sequence.
- The player watches the sequence and repeats it by clicking colored buttons.
- Correct repetition leads to the next level with a longer sequence.
- Wrong input ends the game and displays the score.

## Key Functions

- **levelUp()**: Advances the game level, adds a new color to the sequence, and updates the UI.
- **btnFlash()**: Flashes a button to highlight colors in the sequence.
- **btnPress()**: Handles user button clicks and checks sequence correctness.
- **checkAns()**: Compares user input with the generated sequence.
- **reset()**: Resets the game state to start anew.

---

This concise README helps explain the game clearly and effectively without overwhelming details.
