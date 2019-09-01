# String format

### Example 1
```python
print("your name is %s and family is %s" % (name, family))
```

### Format with format() function

The format() function formats the specified value(s) and insert them inside the string's placeholder.

The placeholder is defined using curly brackets: {}.

The format() method returns the formatted stri

### Example 2
```python
txt1 = "My name is {fname}, I'am {age}".format(fname = "John", age = 36)
txt2 = "My name is {0}, I'am {1}".format("John",36)
txt3 = "My name is {}, I'am {}".format("John",36) 
```


### Example 3
```python
txt = "The universe is {:_} years old."

print(txt.format(13800000000))
```
