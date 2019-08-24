# String operations

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
