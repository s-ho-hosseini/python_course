# File Handling

f = open("demofile.txt","r")

    "r" - Read - Default value. Opens a file for reading, error if the file does not exist

    "a" - Append - Opens a file for appending, creates the file if it does not exist

    "w" - Write - Opens a file for writing, creates the file if it does not exist

    "x" - Create - Creates the specified file, returns an error if the file exists

## Read File

#### Example 1

```python
f = open("demofile.txt", "r")
print(f.read())
```

#### Example 2

```python
f = open("demofile.txt", "r")
print(f.read(5))
```

#### Example 3

```python
f = open("demofile.txt", "r")
print(f.readline())
print(f.readline())
```

#### Example 4

```python
f = open("demofile.txt", "r")
for x in f:
  print(x)
```

#### Example 5

```python
f = open("demofile.txt", "r")
print(f.readline())
f.close()
```

## Write File

#### Example 6

```python
f = open("demofile2.txt", "a")
f.write("Now the file has more content!")
f.close()

#open and read the file after the appending:
f = open("demofile2.txt", "r")
print(f.read())
```

#### Example 7

```python
f = open("demofile3.txt", "w")
f.write("Woops! I have deleted the content!")
f.close()

#open and read the file after the appending:
f = open("demofile3.txt", "r")
print(f.read())
```
