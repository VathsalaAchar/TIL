## Finding Divisors, Proper Divisors or Divisor Count

### Proper Divisor
```python
from sympy import proper_divisors

print(proper_divisors(6)) # => [1, 2, 3]
```


### Divisor

```python
from sympy import divisors

print(divisors(6)) # => [1, 2, 3, 6]
```


### Divisor Count


```python
from sympy import divisor_count, proper_divisor_count

print(divisor_count(6)) # => 4

print(proper_divisor_count(6)) # => 3
```
