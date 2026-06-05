## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```python3
dict1 = eval(input())
dict2 = eval(input())
dict2.update(dict1)
print(dict2)
```

## Output
<img width="1193" height="858" alt="image" src="https://github.com/user-attachments/assets/46799e5e-2409-4bcb-8d46-7bc2e5a05935" />

## Result
Thus the python program that merges **two dictionaries** and combines their key-value pairs is completed successfully.
