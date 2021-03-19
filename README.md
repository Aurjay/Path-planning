## Robotics Path-planning
In this repository we implement various path planning techniques like Random Search Depth-First search,Breadth-First search and A* search by using python.

## Steps for Random Search:
1.Determines the next possible moves from current position.
2.Check if any of next possible moves are goal point.
3.Execute the next possible move.
4.Now that we are in new location we repeat the process.

## Steps for Breadth First Search:
1.Determines the next possible moves from current position.
2.Check if any of next possible moves are goal point.
3.Execute the move with lowest depth.
4.Now that we are in new location we repeat the process.

# Heuristic Value:
It is a value that indicates which of the potential next moves is the most promising to explore.Here we need to have an idea of what the goal point looks like.In simple words it estimates the cost of the cheapest path from any given point to the goal point.
Heuristic Value = (Distance already travelled)+(Best estimate of distance to goal)

# Steps for A* Search:
1.Determines the next possible moves from current position.
2.Check if any of next possible moves are goal point.
3.Execute the move with lowest heuristic value.
4.Now that we are in new location we repeat the process.
#Ideal path calculation = Cost of the path(g(n)) + Heuristic Value(h(n)).
