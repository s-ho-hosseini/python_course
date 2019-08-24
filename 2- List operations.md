# List operations


## Index()
For finding an item location in a collection you can use index.

### Example 1
```python
names = ["ali", "mohsen", "hasan"]

print(names.index("mohsen"))
```
Output : 1


### Example 2
```python
names = ["ali", "mohsen", "hasan"]

print(names.index("mostafa"))
```
Output : OOPS!  Errrrrrrorrr

Unlike other programming languages if index of an element not found this function returns error. For solving that we can check if element exists, we can use index.

```python
names = ["ali", "mohsen", "hasan"]

if "mostafa" in names:
    print(names.index("mostafa"))
```

## Count()
The count() method returns the number of elements with the specified value.

### Exapmle 3
```python
points = [1, 4, 2, 9, 7, 8, 9, 3, 1]

x = points.count(9)
```
