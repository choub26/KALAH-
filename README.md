# KALAH-GAME
KALAH also called MANCALA is a game played on a board of two rows, each consisting of six round pits that have a 
large store at either end called kalah.  
The object of the game is to capture more seeds than one's opponent.

Discover more about the rules of the game on [this file](https://github.com/choubari/KALAH-GAME/blob/master/rules.txt) .

[Mouad FAKHRI](https://github.com/moadfakhri) and I ( [Kawtar CHOUBARI](https://github.com/choubari) ) have coded this game on C language with a graphic interface using SDL 2.0 .
The interface is shown on French as it was a school project for ENSIAS (National School of Applied Sciences in Rabat, Morocco).


# :camera: Interfaces

When you open the game, this is the home interface where there is a Play button *(Jouer)* at the buttom of the window. 

![alt text](images/outputs/home.PNG)

Then, you can choose between playing a new game *(nouvelle partie)* or loading one *(charger une partie)*.

![alt text](images/outputs/choice.PNG)

If you choose creating a new game, you can fill some information to play : name of the game, number of seeds initialized on each pit, name of the first and second player.
An UNDO *(revenir à l'arrière)* and NEXT *(suivant)* buttons are placed at the buttom of each frame.

![alt text](images/outputs/JEU.PNG)
![alt text](images/outputs/nbpieces.PNG)
![alt text](images/outputs/player1.PNG)
![alt text](images/outputs/player2.PNG)

And here is it, you can start playing with your friend. The name of the player who's turn to play is written on red.

![alt text](images/outputs/board.PNG)

However, if you choose loading a previous game, a list of games saved previously is shown like so, you can type a valid name to continue playing.

![alt text](images/outputs/loadgame.PNG)

On the main game, there is a home icon right up, if you click on it, a menu is shown where you can either create a new game, load one or resume the previous one *(reprendre la partie)*.

![alt text](images/outputs/UNDO.PNG)
![alt text](images/outputs/reprendre.PNG)

Here is the winner interface after the end of the game.

![alt text](images/outputs/WINNER.PNG)


# :iphone: Coding interfaces

We've organised each frame as a menu linked by buttons, here is the summary:

![alt text](images/outputs/11.PNG)

The different types of buttons used:

![alt text](images/outputs/22.PNG)


# :wrench:Tools

![alt text](images/tools.png)


