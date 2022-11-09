# flutter_tic_tac_toe

Tic Tac Toe in Flutter

Game initialize with currentPlayer, gameEnd and 9 empty container that will be filled after user click on it.

Took text to show game name and current player.

GridView for 9 container.

If container is not clicked then it's color will be black26,
if container is clicked by player-x, then color will be blue
and if clicked by player-y, then color will be orange.

if container is empty, and winner not allocated, then player can tap on empty box
and after clicking the player will be change.
and also checking plyers winner position.

Winner logic:
The code is checking for a winner in the game.
It starts by creating an array of lists with all possible combinations of player positions, and then it loops through each list to see if there is a winning position.
If there is one, then the code will show a message saying that Player $playerPosition0 Won and end the game and also showing snackbar.

When winner is allocated, and still container is empty, and you want to click on it, then it will play beep sound.
