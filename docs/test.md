# Bac à sable

# Code
``` python hl_lines="3 4"
""" Bubble sort """
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

# Test 

Test latex $f(x)=2x$

$$\frac{n!}{k!(n-k)!} = \binom{n}{k}$$
