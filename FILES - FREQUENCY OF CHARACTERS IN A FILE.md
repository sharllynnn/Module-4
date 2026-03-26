# Exp.No:4d
## FILES - FREQUENCY OF CHARACTERS IN A FILE
---
### AIM  
To write a Python program to read a file and count the frequency of each character in it.

---
### ALGORITHM
1. Begin the program.  
2. Define the function `create_file(file_path, content)`:  
   - Open the file specified by `file_path` in write mode (`'w'`).  
   - Write the provided `content` into the file.  
3. Define the function `char_frequency(file_path)`:  
   - Initialize an empty `defaultdict(int)` to store character frequencies.  
   - Open the file in read mode (`'r'`) and read its content.  
   - Loop through each character in the content and increment its count in the dictionary.  
   - Return the dictionary containing character frequencies.  
4. Accept file content from the user using `input()`.  
5. Call `create_file()` to write the content to the file.  
6. Call `char_frequency()` and print the result.  
7. Terminate the program.

---
### PROGRAM
```python
# Reg.No- 212222060100
# Name- Jothivanan T
from collections import defaultdict

def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def char_frequency(file_path):
    a = defaultdict(int)
    with open(file_path, 'r') as file:
        content = file.read()
        for c in content:
            a[c] += 1
        return a

file_path = 'example.txt'
file_content = input()
create_file(file_path, file_content)
print("Character frequencies:", char_frequency(file_path))
```

### OUTPUT

<img width="1244" height="319" alt="image" src="https://github.com/user-attachments/assets/15a2fb6f-61bc-40e2-9437-745eb5875dd3" />

### RESULT
Thus, the Python program to read a file and count the frequency of each character has been successfully executed and the output is verified.
