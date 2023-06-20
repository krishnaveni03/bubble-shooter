# bubble-shooter

It is a simple game developed using python
Here the datastructure concept is used like graph and array
**DATA STRUCTURE IMPLEMENTATION IN THIS GAME**
An undirected, connected graph where each node is a bubble. Which
bubbles (if any) should fall now? after some arbitrary bubbles are popped and
corresponding nodes are removed from the graph. all bubbles that were just
disconnected from the graph should fall. However the graph approach might
be overkill. Perhaps being able to grab a list of neighboring bubbles in
constant time for a particular "bubble slot" is useful. So the collision
detection would be something like "moving bubble is closest to slot ij,
neighbors of slot ij are bubbles a,b,c, moving bubble is sufficiently close to
bubble b hence moving bubble should come to rest in slot ij".
Here the bubble is considered as vertices and the distance between the
balls is edges. Also here the arrangement of balls in bricks is in array
structure.
PACKAGE USED: 
tkinter for GUI
time and random
GAME WINNER CONDITION:
If the ball hits all the bubble without falling down with the help of the
paddle it means the players is the winner orelse the player can secure
highscores which it also seems to be winner

