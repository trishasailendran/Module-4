# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM


```
#Reg.no 212222060280
#Name Trisha S

user_input = input()
grades_str = user_input.split(',')
try:
    grades = [int(g) for g in grades_str]
    print(grades)
except ValueError:
    print("The grades you entered were in an invalid format.")
    print(grades_str)

```

### OUTPUT

<img width="813" height="176" alt="image" src="https://github.com/user-attachments/assets/eca052b3-5fa7-4051-9aeb-b751c8fdbe1e" />

### RESULT
Thus, a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers are verified.
