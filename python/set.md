# Sets

````python
a = set([4, 5, 6, 9, 2])

len(a)                                           # O(1)
a.add(7)                                         # O(1)
v = 9
v in a                                           # O(1)
a.remove(6)                                      # O(1)
a.discard(5)                                     # O(1)
a.pop()                                          # O(1)
a.clear()                                        # O(1)

b = [1, 3]
set(b)                                           # O(len(b)) => O(N)

a == b                                           # O(N)
a != b                                           # O(N)
a < b                                            # O(N)
a <= b                                           # O(N)
a > b                                            # O(N)
a >= b                                           # O(N)
a | b                                            # O(len(a) + len(b)) => O(M + N)
a & b                                            # O(len(a) + len(b)) => O(M + N)
a - b                                            # O(len(a) + len(b)) => O(M + N)
a ^ b                                            # O(len(a) + len(b)) => O(M + N)
a.copy()                                         # O(N)
min(a)                                           # O(N)
max(a)                                           # O(N)
for v in a                                       # O(N)
````
