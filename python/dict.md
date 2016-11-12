# Dictionaries

````python
a = {
    'i': 4,
    'j': 5,
    'k': 6,
    'l': 9,
    'm': 2
}

a['i']                                           # O(1)
a['i'] = 1                                       # O(1)
len(a)                                           # O(1)
del a['i']                                       # O(1)
a.get('j', 10)                                   # O(1)
a.setdefault('i', 1)                             # O(1)
a.pop('i')                                       # O(1)
a.popitem()                                      # O(1)
v = 9
v in a                                           # O(1)
a.clear()                                        # O(1)
a.keys()                                         # O(1)
a.values()                                       # O(1)
a.items()                                        # O(1)

b = [('c', 1), ('d', 3)]
set(b)                                           # O(len(b)) => O(N)

for v in a                                       # O(N)
for v in a.keys()                                # O(N)
for v in a.values()                              # O(N)
for v in a.items()                               # O(N)
for k, v in a.iteritems()                        # O(N)
````
