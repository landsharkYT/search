Q1: Implemented depthFirstSearch using a Stack and a visited set for graph search.

Q2: Implemented breadthFirstSearch using a Queue and a visited set for graph search.

Q3: Implemented uniformCostSearch using a PriorityQueue ordered by cumulative path cost.

Q4: Implemented aStarSearch using a PriorityQueue ordered by f(n) = g(n) + h(n).

Q5: Implemented CornersProblem where the state is (position, visited_corners_tuple) and the goal is all corners visited.

Q6: Implemented cornersHeuristic using the Manhattan distance to the nearest unvisited corner plus the MST cost over remaining unvisited corners.

Q7: Implemented foodHeuristic as the maximum maze distance from Pacman to any remaining food dot. This is admissible, consistent, and expanded 4137 nodes on trickySearch.

Q8: Implemented findPathToClosestDot using BFS on AnyFoodSearchProblem, and set the goal test to check if the position contains food.
