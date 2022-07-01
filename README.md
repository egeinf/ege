# 25
```python
for x in range(12340000, 12349999):
  x = str(x)
  if x[-1] == '4' and x[-2] == '5':
    x = int(x)
    if x % 21 == 0:
      print(x, x // 21)

# 1234*54
# 100_000_000
# 012345678
```
