# Sets

A set is a collection which is **unordered** and **unindexed**.
In Python sets are written with curly brackets.

### Example 1
```python
thisset = {"apple", "banana", "cherry"}
```

### Example 2
```python
thisset = {"apple", "banana", "cherry"}

for x in thisset:
  print(x) 
```

### Change Items
Once a set is created, you cannot change its items, but you can add new items.


**Add Items**
To add one item to a set use the add() method.
To add more than one item to a set use the update() method.

### Example 3
```python
thisset = {"apple", "banana", "cherry"}
thisset.add("orange")
thisset.update(["orange2", "mango", "grapes"])
```

### Remove Item


**Note** If the item to remove does not exist, remove() will raise an error.

**Note** If the item to remove does not exist, *discard()* will **NOT** raise an error.

### Example 4
```python
thisset = {"apple", "banana", "cherry"}
thisset.remove("banana")
```
**Note** We also can use pop(), clear() and del in sets.
**Note** It is also possible to use the set() constructor to make a set.

### Sets mathematic operations

### Example 5
```python 
numbers = {1, 2, 3}
first = set(numbers)
second = {1, 6}
print(first | second)
print(first & second)
print(first - second)
print(first ^ second)

```

**Note** Set object does not supoort index.
### Example 6
```python
a_set = {1, 3}

print(a_set[1])
```
Output: OOPS , Raise an error.

**Note** If you want to check to existing an item you can use in keywod.
### Example 7
```python
a_set = {1, 3}

if 3 in a_set:
	print("OK")
```

