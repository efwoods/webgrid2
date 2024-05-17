# webgrid2
This is an improvement on webgrid.

## Notes on the original webgrid:
1. Constant values:
   - Time is 1 minute 10 seconds
   - There are either 30 x 30 squares or 12 x 12 squares
   - The squares turn grey and follow the mouse until clicked
   - Clicking correctly on a blue square increases the NTPM (Number of targets per minute)
   - Clicking incorrectly decreases the NTPM (Number of targets per minute)
   - Clicking incorrectly flashes a red box on the incorrect clicked position
   - Clicking correctly places a new blue target box at a random location

2. Alternative values:
- A 30x30 grid:
  - yields an increase of BPS of .16333333 for each correct click
  - decreases BPS by .163333 for each incorrect click
- A 12x12 grid:
  - Increases the value of BPS by .12 for each correct click
  - Decreases the value of BPS by .12 for each incorrect click
 
## Imagined Features
1. A leaderboard with names and scores
2. Visualizing each mouse movement & showing the movements of the mouse after the game has been completed
3. Selecting grid sizes
4. Increasing or decreasing time
5. Add squares to avoid mousing over (optional). Mousing over a square to avoid decreases the score the same as if you clicked an incorrect square.
6. Adding squares that have tiers of value (clicking a purple square has more value than clicking a blue square) (optional) These squares may appear briefly on the screen (for a single second)
7. login system
8. (abstract) train a neural network using the aggregate logging data of multiple players (each player creates a record of how they played and this is used to train an AI to play the game better than any human.
9. logging system (save each moveset by a player)
