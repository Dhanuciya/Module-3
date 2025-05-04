# Regex in Python: Filter Words Without the Letter 'e'
NAME: DHANUCIYA .J 
---
REG NO: 212224020010
---
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
import re
l1=[]
items=['goal' , 'new' , 'user' , 'silt' , 'eat' , 'dinner']
for i in items:
    if not re.search(r"e" , i):
        l1.append(i)
print(l1)
    
## Output
![image](https://github.com/user-attachments/assets/237d7fc2-dfbf-4364-9e1e-4fdb6cbae77d)

## Result
Thus,the program has been executed successfully.
