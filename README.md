# tic-tac-toe

The code features a Tic Tac Toe game against a simple artificial intelligence.
This is an enhancement version of a Python implementation of the game found here:
https://inventwithpython.com/chapter10.html

Thanks to the original author: Al Sweigart, for sharing the materials online for free!

Enhancements:
1. The nine places on the board are not labeled. To aid the human player to make his move, the first enhancement is to show the numbers of the 9 places on the board. 

2. Currently there is no way for the human player to stop the current game once it is started. The second enhancement is to add an option for the human player to stop the game when he enters -1.

3. When the human player enters a wrong number, say 10, or the space is already taken, the program will prompt the user for another input. However, the message prompt is the same for both cases. The third enhancement is therefore to give different messages for these two cases. 

4. After the human player enters his number, the board will be updated with the human player’s move as well as the computer player’s next move. Often it is hard to see both changes at the same time. In the fourth enhancement, the program will wait for the human player to enter anything for the program to display the computer player’s move. 
