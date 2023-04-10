The code is written based on the course CS50’s Introduction to Artificial Intelligence with Python

In this project, we are trying to solve the search problem by finding a sequence of steps to go from a starting point A to a destination point B. We are firstly exploring the two algorithms depth-first search (DFS) and breadth-first search (BFS). A DFS algorithm focuses on exploring a single path thoroughly before moving on to another path, whereas a BFS algorithm explores multiple paths simultaneously by taking one step in each possible direction before moving on to the second step in each direction. In the code, the two algorithms can be changed by modifying the data structure of the frontier to stack (last-in first-out) for DFS and to queue (first-in first-out) for BFS.

The code can be run by:
  python maze.py maze.txt

where maze.txt contains the structure of the maze you want to solve with A is the starting point, B is the destination and # is wall.
