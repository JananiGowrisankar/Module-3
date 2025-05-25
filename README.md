# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```
numbers = [10, 20, 30, 40, 50]
total = sum(numbers)
print("The total is:", total)

```

## Output

![image](https://github.com/user-attachments/assets/60e441e5-97ce-4866-96af-2e62c264c6e5)


## Result
thus a Python program that calculates the **sum of all elements** in a list is successfully verified.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Filtered list (words without 'e'):", l1)
```
## Output

![image](https://github.com/user-attachments/assets/dfebec20-4e29-4ad6-ac85-cdb0bf3e12bc)

## Result
Thus a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is successfully verified.
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(s):
    n = int(input("Enter the index to remove: "))
    a = ""
    for i in range(len(s)):
        if i != n:
            a += s[i]
    return a
input_string = input("Enter a string: ")
result = remove(input_string)
print("Modified string:", result)


## Output

![image](https://github.com/user-attachments/assets/a0244b80-6be5-42b7-bd40-0c70e57eccb4)

## Result

Thus a Python program that accepts a string and removes the character at a specified index is successfully verified.
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
```
s = "google"
reversed_s = s[::-1]
if s == reversed_s:
    print("The string is a palindrome.")
else:
    print("The string is not a palindrome.")
```

## Output

![image](https://github.com/user-attachments/assets/60b76c5c-a5a3-4c93-887e-9d41f774f48a)


## Result
Thus a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions is successfully verified.
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```
x = ('a', 'n', 'c', 3, 8, 5)
is_n_present = 'n' in x
is_8_present = 8 in x
print("'n' in tuple:", is_n_present)
print("8 in tuple:", is_8_present)
```

## Output

![image](https://github.com/user-attachments/assets/54e75e7e-2ff7-4e9b-acd4-87f4debcdd12)


## Result
Thus  a Python program that checks if the element `'n'` and the element `8` exist within a given tuple is successfully verified.
