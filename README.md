# python

## while

#### Simple while
```python
a = 0

while a<10:
    print(a)
    a = a + 1
```

#### While with break
```python
a = 1

while True:
    print (a)
    a = a + 1
    if a>10:
        break
```

## list / array

**Remove an entry from list**
```python
fruitlist = ["appel", "aardbei", "banaan", "framboos", "kers", "banaan"]

print(fruitlist)

fruitlist.pop(0)

print(fruitlist)
```
__Result__
```text
['appel', 'aardbei', 'banaan', 'framboos', 'kers', 'banaan']
['aardbei', 'banaan', 'framboos', 'kers', 'banaan']
```

**Add entry to the list**
```python
fruitlist = ["appel", "aardbei", "banaan", "framboos", "kers", "banaan"]

fruit = "orange"

print(fruitlist)

fruitlist.append(fruit)

print(fruitlist)
```

**Result**
```text
['appel', 'aardbei', 'banaan', 'framboos', 'kers', 'banaan']
['appel', 'aardbei', 'banaan', 'framboos', 'kers', 'banaan', 'orange']
```

**Split strin to list**
```python
s = input ("Enter his/her name: ")

list_of_friends = s.split(",")
list_of_friends.sort()

for friend in list_of_friends:
    print(friend)
```

**Result**
```text
Enter his/her name: hossein,ali
ali
hossein
```

```python
```
```python
```
