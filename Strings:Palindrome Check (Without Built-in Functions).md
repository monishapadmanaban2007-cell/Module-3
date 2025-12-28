# Strings-Palindrome Check in Python (Without Built-in Functions)
## NAME: MONISHA P
## REF NO: 25018486
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
string = "google"

reverse_string = string[::-1]

if string == reverse_string:

    print("The string is a palindrome")
    
else:

    print("The string is not a palindrome")


## Output
The string is not a palindrome

## Result
Thus, the Python program to check whether the given string "google" is a palindrome or not was executed successfully.
