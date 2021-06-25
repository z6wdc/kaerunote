---
title: pandas value_counts
date: 2021-06-25 00:39:13
tags: ['pandas']
---
[value_counts](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.value_counts.html)

用來計數 `Series` 裡面值出現的次數

```python
s.value_counts()
```

## normalize

`normalize` 設成 True 就會回傳值出現次數佔的比例

```python
s.value_counts(normalize=True)
```

## dropna

`dropna` 設成 False 就會回傳 `NaN` 出現的次數

```python
s.value_counts(dropna=False)
```
