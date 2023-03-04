## Q1

1. 12
2. 19
3. 12



## Q2

```python
if temp < 60 or raining == True:
    return True
return False
```



## Q3

I tested is on vscode and nothing happened.



## Q4

```python
if n < 2：
	return False

for i in range(2, i):
    if n % i == 0:
        return False
    return True
```



## Q5

```python
for i in range(1, n + 1):
    if i % 3 == 0 and i % 5 == 0:
        print("fizzbuzz")
    elif i % 3 == 0:
        print("fizz")
    elif i % 5 == 0:
        print("buzz")
    else:
        print(i)
```



## Q6

```python
def unique_digits(n):
    flag = []
    for i in range(0, 10):
        flag.append(False)
    res = 0
    while n > 0:
        if flag[int(n % 10)] == False:
            flag [int(n % 10)] = True
            res += 1
        n //= 10
    return res

def has_digit(n, k):
    while n:
        if int(n % 10) == k:
            return True
        n //= 10
    return False
    
```

