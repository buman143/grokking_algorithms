### Recap

- Balanced binary search trees (BSTs) offer the same Big O search performance as arrays with better insertion performance.
- The height of a tree affects performance.
- AVL trees are a popular type of balanced BST. Like most balanced trees, AVL trees balance themselves through rotation.
- B-trees are generalized BSTs, where each node can have multiple keys and multiple child nodes.
- B-trees try to minimize seek time by reading more data at a time.

| Data Structure | Search | Insert |
|----------------|--------|--------|
|Sorted Array | $O(\log n)$ | $O(n)$ |
|Linked List  | $O(n)$ | $O(1)$ |
|BST | $O(\log n)$ | $O(\log n)$ |