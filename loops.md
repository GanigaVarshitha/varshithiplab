```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```

    apple
    banana
    


```python
for x in range(6):
  print(x)
else:
  print("Finally finished!")
```

    0
    1
    2
    3
    4
    5
    Finally finished!
    


```python
for x in range(6):
  if x == 3: break
  print(x)
else:
  print("Finally finished!")
```

    0
    1
    2
    


```python
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)

```

    red apple
    red banana
    red cherry
    big apple
    big banana
    big cherry
    tasty apple
    tasty banana
    tasty cherry
    


```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```

    apple
    cherry
    


```python
for x in "banana":
  print(x)
```

    b
    a
    n
    a
    n
    a
    


```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```

    apple
    banana
    cherry
    


```python

```
