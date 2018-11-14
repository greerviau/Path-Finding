# Path Finding

## Description
This program provides a visual demonstration of the process undrgone by Dijkstra and A* (A star)

## Dijkstra
Dijkstra's algorithm works by first adding the starting node to a priority que. It then takes the top node in the priority que and looks at all of the nodes surrounding it. If the nodes are valid positions then they are added to the priority que and the top node in the que is deleted. These nodes that are added to the que also have a knowledge of what node they were explored from (ie. their parent node) This process is continued until a node is discovered with the same location as the finish node. From that node, a path is created by retracing the steps to the starting node. 

![dijkstra](https://user-images.githubusercontent.com/36581610/47543269-5878fa80-d8af-11e8-9651-9262251e1b6d.gif)

## A*
A* works similarly to dijkstra by creating a priority que of nodes and then adding new nodes to the que by exploring the top node on the que. However in A* the nodes are placed into the que with a heuristic of distance to the finish node. This means that the node at the top of the que is always the node closest to the finish node.

![astar](https://user-images.githubusercontent.com/36581610/47543277-60d13580-d8af-11e8-8d89-037ee102ac8d.gif)
