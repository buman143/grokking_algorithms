### Recap

- Divde and conquer (D&C) works by breaking a problem down into smaller pieces. If using D&C on a list the base case is probably an empty array or an array with one element.
- When using quicksort, choose a random element as the pivot. The average runtime for quicksort is $O(n \log n)$.
- Given two algorithms with the same big O runtime, oen can be consistently faster than the other. That's why quicksort is faster than mergesort.
- The constant almost never matters for simple search vs. binary search because $O(\log n)$ is so much faster than $O(n)$ when $n$ grows.

| Algorithm | Runtime |
|-----------|---------|
| quicksort | $O(n \log n)$ |
| mergesort | $O(n \log n)$ |
Note: quicksort is typically faster than mergesort because it hits the average case more often than the worst case.