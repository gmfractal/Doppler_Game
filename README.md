# Doppler Game

Doppler is a clone of the Simon memory game created with Vue.js. The game generates a random pattern sequence at the start of each round which the user must replicate on the coloured segments of the game circle.

The game incorporates reactive elements to keep score and the user's current level, as well as to display feedback messages about the game's current status to the user. As the game progresses, the difficulty increases with each level. The speed at which the pattern sequence for the round is displayed to the user increases allowing for less time for the user to memorize the pattern, and the length of the sequence increases too in proportion to the user's level.

A selection of a coloured segment by the user is not confirmed to the system until a mouse up event. This is to provide for a better user experience, allowing the user to change their selection so long as they have not released the mouse button by moving the cursor to another coloured segment before releasing the mouse button.

## TODO:
- replace Vue.js development version with production version to increase performance
