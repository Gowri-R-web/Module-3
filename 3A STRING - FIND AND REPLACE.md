# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM
---
1. Extract the first three characters of the string using a[:3].

2. Extract all characters from index 4 to the end using a[4:].

3. Concatenate the two parts: a[:3] + a[4:]. (This effectively skips the character at index 3.)

4. Print the resulting string.

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
def remove(a):
    result=a[:3]+a[4:]
    print(result)
```

### OUTPUT
<img width="969" height="265" alt="3A" src="https://github.com/user-attachments/assets/12abc513-b573-4c92-8061-a869b2308d65" />


### RESULT
Thus the Python function to accept a string, identify a word to be replaced, and remove a word provided by the user is successfully verified.
