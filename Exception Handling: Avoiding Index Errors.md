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
Add code here
~~~
list1 = [10, 20, 30, 40]

try:
    print("Accessing index 5:", list1[5])
except IndexError:
    print("You're out of list range")

~~~

## Output
![Screenshot 2025-05-20 113312](https://github.com/user-attachments/assets/d2cca1de-5ea4-4d03-9a73-fe5a506b105f)

## Result
Thus the program has been successfully executed
