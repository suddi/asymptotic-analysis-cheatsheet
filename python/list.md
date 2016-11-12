# Lists

````python
a = [4, 5, 6, 9, 2]

a[0]                                             # O(1)
a[0] = 2                                         # O(1)
len(a)                                           # O(1)
a.append(7)                                      # O(1)
a.pop()                                          # O(1)
a.clear()                                        # O(1)

a[2:4]                                           # O(4 - 2) => O(j - i)
b = [1, 3]
a.extend(b)                                      # O(len(b)) => O(N)
list(b)                                          # O(len(b)) => O(N)

a == b                                           # O(N)
a != b                                           # O(N)
a.insert(0, 5)                                   # O(N)
del a[0]                                         # O(N)
a.remove(6)                                      # O(N)
v = 9
v in a                                           # O(N)
a.copy()                                         # O(N)
a.pop(0)                                         # O(N)
min(a)                                           # O(N)
max(a)                                           # O(N)
a.reverse()                                      # O(N)
for v in a                                       # O(N)

3 * a                                            # O(3N) => O(kN)

a.sort()                                         # O(NlogN)
````
