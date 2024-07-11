### Recap

- Hash tables are fast. We can build a hash table with a hash function and an array.
- Collisions are bad and hash functions need to minimize collisions.
- Hash tables are fast at search, insert, and delete.
- Hash tables are good for modeling relationships.
- You should resize a hash table with a load factor $>0.7&.
- Hash tables are used for caching data.
- Hash tables are good for catching duplicates.

| Action | Hash Table (Average) | Hash Table (Worst) | Arrays | Linked Lists |
| Search | $O(1)$ | $O(n)$ | $O(1)$ | $O(n)$ |
| Insert | $O(1)$ | $O(n)$ | $O(n)$ | $O(1)$ |
| Delete | $O(1)$ | $O(n)$ | $O(n)$ | $O(1)$ |