# 25
![image](https://user-images.githubusercontent.com/70198995/176892351-32341170-5836-4630-bb0b-2eaef64d2959.png)

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
