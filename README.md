# AI_Based_TickTacToe_Game
Built an Artificial Intelligence Model who plays Ticktac game with you...But be careful computer will never loose.

- Implementation of Minimax AI Algorithm on Tic-Tac-Toe

## What is Minimax?
Minimax is a artificial intelligence applied in two player games, such as tic-tac-toe, checkers, chess and go. This games are known as zero-sum games, because in a mathematical representation: one player wins (+1) and other player loses (-1) or both of anyone not to win (0).

## Game Tree
Below, the best move is on the middle because the max value is on 2nd node on left.

<p align="center">
	<img src="tic-tac-toe-tree.png"></img>
</p>

In a more complex game, such as chess, it's hard to search whole game tree. However, Alpha–beta Pruning is an optimization method to the minimax algorithm that allows us to disregard some branches in the search tree, because he cuts irrelevant nodes (subtrees) in search.
