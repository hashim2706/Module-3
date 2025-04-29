# Exp.No:3e
## SEB - SEQUENCE OF UPPERCASE LETTERS

---

### AIM  

Write a Python program to find sequences of Upper case letters joined with a '@'.
---

### ALGORITHM

1.Input: Receive a string input that might contain the target pattern.

2.Define Pattern:

  One or more uppercase letters ([A-Z]+)

  The @ character

  One or more uppercase letters ([A-Z]+)

3.Use Regex:

 Use Python's re module.

4.Apply re.findall() with the pattern: r'\b[A-Z]+@[A-Z]+\b'

5.Return: Output the list of all matching substrings.



---

### PROGRAM

```
import re
string=input()
pattern=r'[A-Z]+@[A-Z]+'
match=re.findall(pattern,string)
if match:
    print("Found a match!")
else:
    print("Not matched!")
```

### OUTPUT

![Screenshot (198)](https://github.com/user-attachments/assets/4ed1f977-58dc-40e0-b4a7-b5939a7e52b7)


### RESULT
Thus,the program to find sequences of Upper case letters joined with a '@' was implemented and executed successfully.
