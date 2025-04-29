# Exp.No:3a
## STRING -   SPLIT STRING

---

### AIM  
Write a Python function that accepts the mail id and breaks the string based on "@" using an appropriate built in function.

---

### ALGORITHM

1.Input: Accept an email address as a string (e.g., "user@example.com").

2.Check: Verify that the email contains the "@" character.

3.Split: Use the built-in split() method to divide the string into two parts at the "@" character.

4.Output: Return the username (before "@") and domain name (after "@") as a tuple.



---

### PROGRAM

```
def splitstring(s1):
    parts=s1.split("@")
    if(len(parts)==2):
        s2,s3=parts
        print(f"['{s2}', '{s3}']")
```

### OUTPUT

![Screenshot (194)](https://github.com/user-attachments/assets/e8c049ce-3f7d-4bb7-803e-b274f127ed4e)


### RESULT
Thus, the program that  accepts the mail id and breaks the string based on "@" using an appropriate built in function was implemented and executed successfully.
