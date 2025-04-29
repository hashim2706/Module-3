# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
a=eval(input())
b=[]
for i in range(5,a,5):
    b.append(i)
print(tuple(b))
```

### OUTPUT

![Screenshot (197)](https://github.com/user-attachments/assets/4a5ded3b-6709-4448-97e3-81517ca5da8f)


### RESULT
Thus ,the program to create a tuple containing all multiples of 5 up to a given number **N** was implemented and executed successfully.
