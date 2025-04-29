# Exp.No:16  
## DICTIONARY

---

### AIM  
To write a Python program that accepts 10 numbers from the user and stores each number as a key in a dictionary with its corresponding value being a list of its divisors. Finally, display the dictionary.


---

### ALGORITHM

Start the program.
Initialize an empty dictionary c.
Repeat the following steps 10 times (using for i in range(10)):
a. Input a number a from the user using int(input()).
b. Initialize an empty list d to store divisors of a.
c. Use a loop for j in range(1, a+1) to check all numbers from 1 to a (inclusive).
d. If a % j == 0, append j to the list d (it is a divisor).
e. Assign the list d as the value for the key a in dictionary c.
After the loop, print the dictionary c which contains numbers as keys and lists of their divisors as values.
End the program.

---

### PROGRAM

```
#Add Your Code Here
c=dict()

for i in range(10):
    d=[]
    a=int(input())
    for j in range(1,a+1):
        if a%j==0:
            d.append(j)
    c[a]=d
print("The dictionary is : d = ", c)


```

### OUTPUT
![image](https://github.com/user-attachments/assets/15173894-6b01-485d-9687-7767dee4d087)


### RESULT
Thus the program DICTIONARY have been executed and verified sucessfully
