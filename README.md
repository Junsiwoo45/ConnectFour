# ConnectFour
---

- Simulates the Connect four game using React and mongoDB
- Creating a game board that is interactive
- Displaying the board as the user interacts with the page
- Checking on every turn to see if a user has one
- Keeping track of the users scores and saving them to the database
- Filtering the database to display the best scores at the top and the worst scores at the bottom

	In this program creates the gam of connect four using React. This game is a two player game that where the first player is marked as X and the second player is marked as O. These are both color coordinated, X is blue and O is teal. The game keeps track of how many moves it takes to win. In order to play the game, you need to click on the column on where you want to drop your first move. The move will drop to the bottom of row that isn’t in play. This is done in code by looping through the array to check to see which area is being used or not, and to also see which player is in that position. After each turn, the color and Sign will flip to indicate which player has moved. The game continues to check to see if the players have connected four in a row from different angles, horizontally, vertically, and diagonally. Once someone wins, it will display who won and how many turns it took to win. A button will appear and will asked the user to add to high scores. If the button is pressed a place to put your username in will appear as well as a position that will show your turns it took win. The high scores will be sent to the mongodb to be saved. Once the button is clicked to save, the high scores table will appear and display who has beaten the game in the lowest amount of turns at the top.
This program does
---

### Winner
![](https://github.com/Junsiwoo45/ConnectFour/blob/main/img/Winner.PNG)

### Create winner
![](https://github.com/Junsiwoo45/ConnectFour/blob/main/img/createWinner.PNG)

### Board is full
![](https://github.com/Junsiwoo45/ConnectFour/blob/main/img/boardfull.PNG)

