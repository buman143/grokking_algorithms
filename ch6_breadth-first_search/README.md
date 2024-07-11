### Recap

- Breadth-first search (BFS) tells you if there's a path from A to B.
- If there's a path, BFS will find the shortest path.
- Problems involving "find the shortest x" can be modeled with a graph and solved by BFS.
- Undirected graphs don't have arrows between vertices, directed graphs do.
- Queues are FIFO and stacks are LIFO.
- The search list needs to be a queue in order to get the shortest path.
- Searched vertices need to be tracked.
- The runtime of BFS is $O(V+E)$ where $V$ is vertices and $E$ is edges.