# Git Tac Toe
One of the first tools we'll use is a version control system called Git, a tool that was written expressly for helping thousands of people around the world co-develop one of the largest and most stable software projects around: the Linux operating system. You can read more about the history of Git and Linux here.

Some of you may have used Git before, perhaps in the Fall and Winter quarter of Upper Division CS. This quarter, we will focus on understanding the concepts and the underlying operation of Git via its graph representation of commits.

To do this, we are going to play the game of tic-tac-toe, which many people used to first learn to play on paper with pen/pencil.

## In-Class Activity
We'll pause here. Pair up with the person next to you, draw a grid that looks like the hash sign # with enough space to write X and O, and take turns drawing your symbols.

Here are rules how to play.

Now, think back on your game and how you would define this problem more precisely so that you could write a program to play the game automatically (a TicTacToeSolver).

Over the next week, we'll use this problem to practice both

version control skills with git
software construction skills to define and write a solver
We'll call it Git-Tac-Toe (groans are appropriate here) and play it on an ASCII grid that can be stored in plaintext like this.

```
|_|_|_|1
|_|_|_|2
|_|_|_|3
 1 2 3
```
