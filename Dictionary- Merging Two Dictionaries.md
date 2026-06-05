## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```python
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```

## Output











<img width="966" height="290" alt="530331810-fcfb004a-98d5-4eb5-b339-eb4ad0690fbf" src="https://github.com/user-attachments/assets/45a74d29-0575-49f9-82f5-6e30a555f2b3" />

## Result

Thus the program executed successfully.
