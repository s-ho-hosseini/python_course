# Dictionaries - KeyValue pairs

A dictionary is a collection which is **unordered**, **changeable** and **indexed**.
In Python dictionaries are written with curly brackets, and they have keys and values.

### Example 1
```python
thisdict = {
    "brand": "Ford",
    "model": "Mustang",
    "year": 1964
}

print(thisdict)
```


```python
point = {"x": 1, "y": 2}
point = dict(x=1, y=2)
print(point)

point["x"] = 10
point["z"] = 12
print(point)

```

**Note** If you want to use an unexisting key, python raise an error.
For solve that you can check for an existing item.
### Example 2
```python
point = {"x": 1, "y": 2}
if "x" in point:
	print(point["x"])
```

### .get
If you use dictionary get for getting an element. It shows element witout raising error.

### Example 2
```python
point = {"x": 1, "y": 2}
print(point.get("x"))
```
**Note** For deleting an item you can use del.
**Note** For accessing all items you can use for loop.
## Example 3
```python
point = {"x": 1, "y": 2}
for item in point:
	print(point[item])
```

## Example 4
```python
point = {"x": 1, "y": 2}
for k, v in point.items():
    print(k, v)
```
