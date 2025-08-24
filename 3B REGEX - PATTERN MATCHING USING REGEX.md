# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX

---

### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.

---

### PROGRAM

```
# 212223060073
# Gowri Sankari R
import re
str = input()
if re.search(r'^a(b*)$',str):
  print("Found a match!")
else:
   print("Not matched!")
```
### OUTPUT
<img width="1183" height="395" alt="3B" src="https://github.com/user-attachments/assets/cf31b326-5b74-43d9-90c6-ad2152251c4d" />

### RESULT
Thus the Python program that matches a string containing an 'a' followed by two to three 'b' characters using regular expressions is successfully verified.
