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
```
list1=[5, 10, 20]
try:
    print(lst[5])
except:
    print("You're out of list range")
```

## Output
![439088736-32e227b4-d6db-4d30-b45d-fb949d823034](https://github.com/user-attachments/assets/64987b8f-94e2-44da-a110-543609d43a6d)

## Result
Hence the program executed successfully!
