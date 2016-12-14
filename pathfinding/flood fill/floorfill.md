#Flood Fill
###[example](https://jsbin.com/zegisi/edit?output)
This method of pathfinding uses a flood fill algorithm to make a map af the area from the finish to start and then traces from start to finish using the system described in `making a path`

##Making a Path
Starting at the start pos itterate until at finish.
  -check adjacent cells and track which one has the highest value
  -mark the current square as a wall
  -add current spot to path
  -if the current spot is at the position of the finishing point
    -return the path
