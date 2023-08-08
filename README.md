# Algo22

# Breadth-First Search (BFS) 
BFS - is a graph traversal algorithm used to explore and analyze the structure of a graph or tree in a systematic manner. 

It starts from a given starting point (usually a node) and systematically explores all neighboring nodes at the current depth level before moving on to the next depth level. Here's a step-by-step breakdown of how BFS works:

1. Choose a starting node and mark it as visited.
2. Create a queue data structure to keep track of nodes to be explored.
3. Enqueue the starting node into the queue.
4. Enter a loop that continues as long as the queue is not empty:
   a. Dequeue a node from the front of the queue.
   b. Process the dequeued node (e.g., visit or analyze it).
   c. Enqueue all unvisited neighbors of the dequeued node into the queue and mark them as visited.
5. Continue the loop until the queue becomes empty.

## Key points to remember:
- BFS explores nodes level by level, ensuring that all nodes at a certain depth are visited before moving deeper.
- It uses a queue to keep track of the order in which nodes are visited.
- BFS is useful for finding the shortest path between two nodes in an unweighted graph.
- It is also used in applications like social network analysis, shortest path finding, and puzzle-solving algorithms.

Overall, BFS is a methodical approach to exploring a graph by visiting all reachable nodes layer by layer, making it a valuable tool in various computer science and real-world scenarios.


# Depth-First Search (DFS) 

DFS - is a graph traversal algorithm used to explore and analyze the structure of a graph or tree by diving as deep as possible along each branch before backtracking.

It starts from a given starting point (usually a node) and explores as far as possible along each branch before backtracking to explore other branches. Here's a step-by-step breakdown of how DFS works:

1. Choose a starting node and mark it as visited.
2. Create a stack or use recursion to keep track of nodes to be explored.
3. Push the starting node onto the stack or initiate the recursive call.
4. Enter a loop that continues as long as the stack is not empty:

   a. Pop a node from the top of the stack (or during recursive calls).

   b. Process the popped node (e.g., visit or analyze it).

   c. Push all unvisited neighbors of the popped node onto the stack and mark them as visited (or make recursive calls).

6. Continue the loop until the stack becomes empty.

## Key points to remember:
- DFS explores nodes as deeply as possible before backtracking to explore other branches.
- It uses a stack (or recursion) to keep track of the order of nodes to be explored.
- DFS may not necessarily find the shortest path between two nodes in an unweighted graph.
- It is used in applications like searching for solutions in puzzles, backtracking algorithms, and graph-based algorithms.

Overall, DFS is an approach that delves deeply into a graph by fully exploring one branch before moving on to others, making it suitable for various scenarios where exhaustive exploration is needed.
