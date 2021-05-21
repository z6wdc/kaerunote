---
title: Python List Comprehension
date: 2021-05-06 20:18:13
tags: ['Python']
---
在 Python 中有著 List Comprehension 這個更簡潔的 synax

## The Syntax

```python
newlist = [expression for item in iterable if condition == True]
```

例  
列出從 1 - 10 的偶數

```python
numbers = range(10)
even = [x for x in numbers if x % 2 == 0]

print(even)
```
