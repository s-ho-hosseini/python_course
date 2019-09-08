# Functions 

We have seen some built-in funtions in python such as print(), round(), ...

#### Example 1
```python
def greet():
    print("Hello")
    print("How are you?")
```

#### Example 2
```python
def greet(first_name,last_name):
    print(f"Hi {first_name} ")
    print(f"Name {first_name} and family{last_name}")
```

## Default Parameter Value

##### Example 3
```python
def my_function(country = "Norway"):
  print("I am from " + country)
```



## Types of functions 

* Perform a task
* Return a value

#### Example 4 (Return a value)
```python
def get_greeting(name):
    return f"Hi {name}"
```

## Keyword Arguments

#### Example 5

```python
def increment(value,by):
  return value+by

increment(2,by=1) 
```

## Optional parameteres

#### Example 6

```python
def increment(value,by=1):
  return value+by

increment(2) 
```

**Note** : Optional paramateres will be after required parameteres.
