# SCOUT_MINI

## Another heading

### abc

Some `code` goes here.

### Plain codeblock

A plain codeblock:

```
Some code here
def turtlebot4():
//some comments
```

### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def turtlebot4():
//some comments
```

### with a title
``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

### Code block with line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

