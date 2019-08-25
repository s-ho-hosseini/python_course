# Tuples

A tuple is a collection which is **ordered** and **unchangeable(immutable)**.
In Python tuples are written with ( and ).

### Example 1
```python
thistuple = ("apple", "banana", "cherry")
print(thistuple)
```

### Access Tuple Items
You can access tuple items by referring to the index number, inside square brackets.

### Example 2
```python 
thistuple = ("apple", "banana", "cherry")
print(thistuple[1])
```

**Note:** Once a tuple is created, you cannot change its values, add or remove item(s). **Tuples are unchangeable**.

**Note:** When we use tuples to wouldn't change the values of a collection accidently.

### Concatenate tuples
You can cotcatenate two or more tuples with plus(+).

Example 3
```python
point = (1, 2) + (3, 4)
points
```
**Note:** You can create multi item tuples with star(*) operator.

### tuple()
It is also possible to use the tuple() constructor to make a tuple.
The input of that can be any iterable types such as lists and strings.
```python
nums = tuple([1,2])
```
### Swaping variables

```python
x = 10
y = 12
x, y = y, x
```
