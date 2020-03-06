# Python

## The short way
Contibuted by: [BraydonKains](https://github.com/BraydonKains)

This is the way everyone in the Programmer Nullposting group says is the best.

```python
def isEven(x):
    return x % 2 == 0
```
## The p y t h o n i c way
Contributed by: [Angus L'Herrou](https://github.com/angus-lherrou)

What, you aren't using generators? Are you even a python programmer?

```python
def is_even(x):
    return [even for n, even in zip(range(abs(x)+1), gen_even())][abs(x)]

def gen_even():
    even = True
    while True:
        yield even
        even = not even
```

## The long way home
Contributed by: [Hinomupi](https://github.com/Hinomupi)
haha comparisons

```python
def isEven(x):
    if x != x//1:
        return x == x//1
    elif x == x//1:
        if x == 0: return True
        elif x != 0:
            if x != 0 and x == x//1: return isEven(x - abs(x)/x) is not (1 == 1)
```
