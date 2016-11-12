# Tuples

````python
a = (4, 5, 6, 9, 2)

a[0]                                             # O(1)
len(a)                                           # O(1)

a[2:4]                                           # O(4 - 2) => O(j - i)
b = [1, 3]
tuple(b)                                         # O(len(b)) => O(N)

a == b                                           # O(N)
a != b                                           # O(N)
v = 9
v in a                                           # O(N)
min(a)                                           # O(N)
max(a)                                           # O(N)
for v in a                                       # O(N)

3 * a                                            # O(3N) => O(kN)
````
