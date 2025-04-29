# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

Start the program.
Use a try block to:
a. Accept an integer input n (number of list elements).
If a ValueError occurs during conversion, display an appropriate error message.
If input is valid, proceed to:
a. Initialize an empty list a.
b. Use a loop for i in range(n) to:
i. Accept an integer input element and append it to the list.
ii. If a non-integer is entered, a ValueError will be caught.
Print the list a.
Ask the user to enter an index number to access an element from the list.
Use another try block to:
a. Attempt to print the element at the given index.
Catch an IndexError if the index is out of range and print a custom message.
End the program.

---

### PROGRAM

```
Add Your Code Here
try:
    n = int(input(""))
    
    a = []
    for i in range(n):
        element = int(input(""))
        a.append(element)
    
    print(a)
    
    indexno = int(input(""))
    
    try:
        print(a[indexno])
    except IndexError:
        print(f"{indexno} is not accepted")
    
except ValueError as e:
    print("Invalid input. Please enter a valid integer.")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/a0d49975-c1b9-4b8a-a335-2405488718c2)

### RESULT
Thus the program EXCEPTION HANDLING have been executed and verified.
