# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```python3
try:
    n=int(input())
    l=[]
    for i in range(n):
        l.append(int(input()))
    print(l)
    print(l[6])
except IndexError:
    print("6 is not accepted")
```

## Output
<img width="1543" height="854" alt="image" src="https://github.com/user-attachments/assets/87e77317-f328-4ba8-92d3-cc06eec4809d" />

## Result
Thus the python program that handles an **IndexError** when trying to access an element beyond the available range of a list is completed successfully.
