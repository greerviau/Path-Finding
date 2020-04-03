# Path Finding

## Description
This program provides a visual demonstration of the process undergone by Dijkstra and A* (A star)

### [YouTube Video](https://www.youtube.com/watch?v=xGdBwdd_FLc&t)

## Dijkstra
Dijkstra's algorithm works by first adding the starting node to a priority queue. It then takes the top node in the priority queue and looks at all of the nodes surrounding it. If the nodes are valid positions then they are added to the priority queue and the top node in the queue is deleted. These nodes that are added to the queue also have a knowledge of what node they were explored from (ie. their parent node) This process is continued until a node is discovered with the same location as the finish node. From that node, a path is created by retracing the steps to the starting node. 

![dijkstra](https://user-images.githubusercontent.com/36581610/50039437-a6cd8e80-0000-11e9-865a-1c6062046d4f.gif)

## A*
A* works similarly to dijkstra by creating a priority queue of nodes and then adding new nodes to the queue by exploring the top node on the queue. However in A* the nodes are placed into the queue with a heuristic of distance to the finish node. This means that the node at the top of the queue is always the node closest to the finish node.

![astar](https://user-images.githubusercontent.com/36581610/50039438-af25c980-0000-11e9-9fda-f96a2ee6cb2e.gif)

## Draw a maze
![drawmaze](https://user-images.githubusercontent.com/36581610/51815322-197f8a00-228e-11e9-80c9-b088d76b3ba2.gif)

