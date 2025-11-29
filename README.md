# Big O Practice Problems

## 1. What is the runtime efficiency of the following pseudo code in Big O?

### a.
```pseudo
list = ['apples', 'bananas', 'cucumbers', 'daikon']
for item in list:
    print("I have five", item)
```
`O(1)` — list has fixed size.

### b.
```pseudo
list = ['apples', 'bananas', 'cucumbers', 'daikon', ...]
for item in list:
    print("I have five", item)
```
`O(n)` — loop depends on list length, which is not fully defined.

### c.
```pseudo
print("Hello!")
```
`O(1)` — constant-time print.

### d.
```pseudo
function square(n)
    for i in range(n)
        for j in range(n)
            print(n, end="")
    print()
```
`O(n²)` — nested loops each run `n` times.

### e.
```pseudo
function search(list)
    for i in range(3, len(list))
        if list[i] == 3
            return 0
    return 1
```
`O(n)` — linear scan from index 3 to end.

### f.
```pseudo
x = 80
while x > 1
    x -= 2
```
`O(1)`

### g.
```pseudo
while x > 1
    x -= 2
```
`O(n)`

### h.
```pseudo
n = 100
for i = 0; i < n; i++
    for j = n; j > 1; j--
        print(i, ":", j)
```
`O(1)`

### i.
```pseudo
for i = 0; i < n; i++
    for j = n; j > 1; j--
        print(i, ":", j)
```
`O(n²)`

---

## 2. Given the following equations for the number of operations, what is the Big O?

a.  
```
4
```
→ `O(1)`

b.  
```
6n + 67
```
→ `O(n)`

c.  
```
23 + 45
```
→ `O(1)`

d.  
```
n³ + 4n² − 3n + 5
```
→ `O(n³)`

e.  
```
n⁴ + 300n² + 30
```
→ `O(n⁴)`

f.  
```
2ⁿ + 2n² + 2
```
→ `O(2ⁿ)`

---

## 3. Fill in the following table with the *worst case* number of visits in Big O notation

| Operation | Contiguous Unordered Array | Non-contiguous Unordered Array | Contiguous Ordered Array | Non-contiguous Ordered Array |
|----------|-----------------------------|--------------------------------|---------------------------|-------------------------------|
| **Read** | `O(1)` | `O(1)` | `O(1)` | `O(1)` |
| **Search** | `O(n)` | `O(n)` | `O(log n)` (binary search) | `O(n)` (no locality/fast indexing) |
| **Insert** | `O(1)` | `O(1)` (pointer-based) | `O(n)` (maintain order) | `O(n)` |
| **Delete** | `O(1)` | `O(1)` (pointer-based) | `O(n)` (maintain order) | `O(n)` |
