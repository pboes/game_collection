---
layout: page
title: "Lielow"
permalink: lielow
---
## Description

Lielow is a finite and drawless checkmate game played with stackable checkers instead of differentiated pieces. It was invented by Alek Erickson and Michael Amundsen in the summer of 2021.

## Rules

Each turn you must move one of your stacks, in a straight line orthogonally or diagonally, a distance exactly equal to the size of that stack.
If it lands on an empty space, the stack grows by 1.
If it lands on an enemy, the enemy is removed and your stack shrinks down to size 1.
It is not legal to land on a friendly stack.
Jumping over stacks is allowed.
Stacks may also jump off the board, removing themselves from the game.
Passing is not allowed.

Definitions for crown and king: In this implementation, the king-stack will have a red stroke color. This red ring is the crown. Which stack has the crown is determined like this: After your move, if there is, among your stacks, a unique stack of the biggest size, the crown will be on that stack. There is no other way the crown can change heads. The piece with a crown on it is the king.

Goal: If the enemy king is removed from the game, you win.

Note: In this implementation, jumping off the board is only possible if the stack can reach exactly 1 row or column beyond the perimeter. But it seems to always be the case that it is possible to jump off the board when a stack is big enough. Please let Michael know if you encounter a scenario where a piece is stuck. This should not be allowed according to the rules of the game.

[Ludii Link](https://ludii.games/details.php?keyword=Lielow)
