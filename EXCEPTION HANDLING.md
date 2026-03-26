# Exp.No:4c
## EXCEPTION HANDLING
---
### AIM  
To write a Python program to check if the value given in age as input is negative and raise an exception using the `raise` keyword.

---
### ALGORITHM
1. Begin the program.  
2. Accept an integer input `age` from the user.  
3. Print `"Age is:"` and the entered age.  
4. Use a `try` block to check if `age` is negative.  
5. If `age` is negative, raise an exception using the `raise` keyword with the message `"Input Correct age."`.  
6. Catch the exception in the `except` block and print the error message.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
try:
    age = int(input())
    print("Age is:")
    print(age)
    
    if age < 0:
        raise ValueError("Input Correct age.")
    else:
        year_of_birth = 2022 - age
        print("Year of Birth is:")
        print(year_of_birth)
        
except ValueError as e:
    print(e)
```

### OUTPUT
<img width="474" height="252" alt="image" src="https://github.com/user-attachments/assets/65587acc-cd0f-490a-b51a-58c172c2493c" />


### RESULT
Thus, the Python program to check if the age value is negative and raise an exception using the `raise` keyword has been successfully executed and the output is verified.
