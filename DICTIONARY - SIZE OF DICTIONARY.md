# Exp.No:4b 
## DICTIONARY - MERGE DICTIONARIES
---
### AIM  
To write a Python program to merge dictionary2 with dictionary1.

---
### ALGORITHM
1. Begin the program.  
2. Accept two dictionaries `dict1` and `dict2` from the user using `eval()`.  
3. Merge `dict2` into `dict1` such that keys from `dict1` take priority over `dict2`.  
4. Print the merged dictionary.  
5. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
dict1 = eval(input())
dict2 = eval(input())
merged = {**dict2, **dict1}
print(merged)
```

### OUTPUT
<img width="1343" height="200" alt="image" src="https://github.com/user-attachments/assets/94e66202-eede-437d-a7bc-d2852ed3fc70" />


### RESULT
Thus, the Python program to merge dictionary2 with dictionary1 has been successfully executed and the output is verified.
