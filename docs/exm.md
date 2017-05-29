# Examples of Yapy programs

## Hello, world!
```python
print("Hello, world!")
```

## Factorial
```python
def fact(n):
  if not n:
    return 1
  else:
    return n*fact(n-1)

nums = [1,2,3,4,5]
print(nums.map(fact))
```

