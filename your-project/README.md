<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Tic Tac Toe Mania
*Lorenzo Fabritius*

*Data Analytics, Barcelona, 17.01.2020*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
I chose to build the game Tic Tac Toe (slightly altered), as it is a widely known game played by people of all ages.

## Rules
Tic Tac Toe is played by 2 players. The players take turns at marking a 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner.

## Workflow
- Define the 3x3 board and visualise it
- Define the player move and visualise it on the board
    - Challenge: I was not able to alter the board after the player move to include the move. I solved this by using a numpy   array and a dictionary. However, as you cannot add letters to an array of integers, I had to adapt and instead of Xs and Os decided to implement recognizable integers "19" and "84".
- Define the cpu move.
- Define winning combinations
    - This was a challenge, as I had to define the winning combinations through a list of tuples referencing a dictionary, referencing an array of 3 rows.
 
- Set the condition so that the game ends if one of the players reaches a winning combination or if the array is full and the game is a tie.

## Organization

See workflow

## Links

[Repository](https://github.com/lorenzofabrit/Project-Week-1-Build-Your-Own-Game)  
[Slides](https://docs.google.com/presentation/d/1fz4qVS-YYTY9lAx04tHxeOt8439PYYBiQpDHGx6xmQk/edit#slide=id.g47b0d096c6_0_53)  
 
