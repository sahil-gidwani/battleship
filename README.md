# battleship
Game: Battleship 
Main task:
The program should allow the user to play Battleship against the computer. The computer places the following 
five types of ship of different lengths on a 10 by 10 board. The types of ship and their lengths are shown below:
1. Aircraft carrier: 5 squares long
2. Battleship: 4 squares long
3. Submarine: 3 squares long
4. Destroyer: 3 squares long
5. Patrol Boat: 2 squares long
The computer should randomly place the ships on the board, vertically or horizontally, taking care that no ship 
overlaps with another ship or is out of the bounds of the 10 by 10 board. The player ‘shoots’ in order to hit and 
sink all the ships of the computer.
A ship sinks when all of its squares have been hit.
The player should enter the X,Y coordinates of a shot. The computer should display the appropriate message
according to the outcome of the shot:
- My ship was hit!
- You missed!
- You sank my [ship type]!
A list of the sunk and un-sunk ships up to that point should also be displayed.
The 10 by 10 board should be visible to the player, but not the ships. That is, at the start of the game, an empty 
10 by 10 board should be displayed. After each shot, the board should be updated by adding an ‘M’ on the 
chosen square, if it was a miss, or an ‘H’, if it was a hit.
The program should keep a running score for the player during the game (the score is set to 0 at the start of the 
game). Each shot (hit or miss) deducts one point from the score; and each hit adds one point; when a ship is 
sunk, a number of points equal to the length of that ship multiplied by 2 is added to the score (for example, +10 
for the aircraft carrier). The game ends when the player has sunk all of ships or if the player enters ‘Quit’. At the 
end of a game, the computer should display the score of the player and ask the player if they want to play again.
Variation: The board also contains two sea monsters, Kraken and Cetus, which will be annoyed if hit. 
If Kraken is hit, it will consume all of the points in the player’s score at the time at which it is hit. If 
Cetus is hit, it will cause all un-sunk ships on the board to move to different places on the board. 
Each sea monster should be placed on a random square (which is not occupied by a ship) immediately 
after the computer has placed the ships on the board. 
