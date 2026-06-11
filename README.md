# Bubble Sort（氣泡排序）

一個簡單的 Python 氣泡排序演算法實作。

## 說明

氣泡排序（Bubble Sort）是一種簡單的排序演算法。它重複地走訪要排序的數列，一次比較兩個元素，如果它們的順序錯誤就把它們交換過來。

## 使用方法

```python
from bubble_sort import bubble_sort

arr = [64, 34, 25, 12, 22, 11, 90]
sorted_arr = bubble_sort(arr)
print(sorted_arr)
```

## 執行

```bash
python bubble_sort.py
```

## 範例輸出

```
Original: [64, 34, 25, 12, 22, 11, 90]
Sorted:   [11, 12, 22, 25, 34, 64, 90]
```
