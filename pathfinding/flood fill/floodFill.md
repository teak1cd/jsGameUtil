#Flood Fill
###[example](https://jsbin.com/zegisi/edit?output)
This method of pathfinding uses a flood fill algorithm to make a map af the area from the finish to start and then traces from start to finish using the system described in `making a path`

##Making a Path
Starting at the start pos itterate until at finish.
  1. check adjacent cells and track which one has the highest value
  2. mark the current square as a wall
  3. add current spot to path
  4. if the current spot is at the position of the finishing point then return the path

##Flood Fill
for this example I used a four direction flood fill algorithm
