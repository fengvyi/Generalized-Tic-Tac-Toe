# Generalized-Tic-Tac-Toe
A generalized Tic Tac Toe is an n\*n board game where each player chooses one of the parts X or O, and then plays in an alternate order to place his choice on the board. A player wins when he places m parts of	his	choice in	a	consecutive	order. The game may end in a draw when no one wins.	
Given m and n, the agent can play against another agent in an n\*n board and tries to place m parts in a row to win.	  

### Algorithm
Minimax with Alpha-Beta Pruning

### Evaluation function
We define an evaluation function based on the idea of counting winning
windows, which definition can be found in [this article](https://web.stanford.edu/class/cs221/2017/restricted/p-final/xiaotihu/final.pdf). I made further improvements that only update the winning windows and board scores containing the current move.
