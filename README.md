# Big O Practice Problems

## 1. What is the runtime efficiency of the following pseudo code in Big O?

### a.
```pseudo
list = ['apples', 'bananas', 'cucumbers', 'daikon']
for item in list:
    print("I have five", item)
```

### b.
```pseudo
list = ['apples', 'bananas', 'cucumbers', 'daikon', ...]
for item in list:
    print("I have five", item)
```

### c.
```pseudo
print("Hello!")
```

### d.
```pseudo
function square(n)
    for i in range(n)
        for j in range(n)
            print(n, end="")
    print()
```

### e.
```pseudo
function search(list)
    for i in range(3, len(list))
        if list[i] == 3
            return 0
    return 1
```

### f.
```pseudo
x = 80
while x > 1
    x -= 2
```

### g.
```pseudo
while x > 1
    x -= 2
```

### h.
```pseudo
n = 100
for i = 0; i < n; i++
    for j = n; j > 1; j--
        print(i, ":", j)
```

### i.
```pseudo
for i = 0; i < n; i++
    for j = n; j > 1; j--
        print(i, ":", j)
```

---

## 2. Given the following equations for the number of operations, what is the Big O?

a.  
```
4
```

b.  
```
6n + 67
```

c.  
```
23 + 45
```

d.  
```
n³ + 4n² − 3n + 5
```

e.  
```
n⁴ + 300n² + 30
```

f.  
```
2ⁿ + 2n² + 2
```

---

## 3. Fill in the following table with the *worst case* number of visits in Big O notation

| Operation | Contiguous Unordered Array | Non-contiguous Unordered Array | Contiguous Ordered Array | Non-contiguous Ordered Array |
|----------|-----------------------------|--------------------------------|---------------------------|-------------------------------|
| **Read** |                             |                                |                           |                               |
| **Search** |                           |                                |                           |                               |
| **Insert** |                           |                                |                           |                               |
| **Delete** |                           |                                |                           |                               |
