# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
Add code here
```
original = "google"
reversed_str = original[::-1]
if original == reversed_str:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```
## Output
![Screenshot 2025-04-30 140719](https://github.com/user-attachments/assets/b55a9d67-b83c-447e-998e-e78d0899c2b0)
## Result
The code executed successfully.
