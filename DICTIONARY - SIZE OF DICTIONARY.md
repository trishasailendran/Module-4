# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM


```
#Reg.no 212222060280
#Name Trisha S

from sys import getsizeof
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
result1 = getsizeof(dic1)
result2 = getsizeof(dic2)
result3 = getsizeof(dic3)
print("Size of dic1: ", result1, "bytes", sep='')
print("Size of dic2: ", result2, "bytes", sep='')
print("Size of dic3: ", result3, "bytes", sep='')

```

### OUTPUT

<img width="818" height="250" alt="image" src="https://github.com/user-attachments/assets/3fbc30ef-8183-4cca-a0eb-2fdc7f1cdc1c" />

### RESULT
Thus, a Python program to print the size of a dictionary using getsizeof() from the sys module are verified.
