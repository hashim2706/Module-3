# Exp.No:3b  
## REGEX - SEQUENCE OF LOWER CASE LETTERS

---

### AIM  
Write a Python program to find sequences of Lower case letters joined with a '@'.

---

### ALGORITHM

1.Input: Accept a string that may contain patterns of interest.

2.Define Pattern: Use a regular expression to match:

3.One or more lowercase letters ([a-z]+)

4.An @ symbol

5.One or more lowercase letters ([a-z]+)

6.Use Regex: Apply re.findall() to extract all matching sequences.

7.Output: Return or print the list of matches.



---

### PROGRAM

```
import re
string=input()
pattern=r'[a-z]+@[a-z]+'
match=re.findall(pattern,string)
if match:
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT

![Screenshot (195)](https://github.com/user-attachments/assets/d9df8ddd-013f-44a5-9f91-14def536217b)

### RESULT
Thus, the program to find sequences of Lower case letters joined with a '@' was implemented and executed successfully.
