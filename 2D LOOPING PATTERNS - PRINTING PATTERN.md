 Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
To write a Python program to print a reversed pyramid pattern in Python using loops.

---

### ALGORITHM

1. Begin the program.  
2. Input the number of rows rows.
3.Loop from i = rows down to 1:
   Print (rows - i) spaces to align the stars properly.
   Print (2 * i - 1) stars (*) on the same line.
4.After each line, move to the next line automatically.
5. Terminate the program.

---

### PROGRAM
```
#Reg.No:212223020028
#Name:Tharani devi.G
#Add Your Code Here
rows = int(input())
k = 2 * rows - 2
for i in range(rows, -1, -1):
    for j in range(k, 0, -1):
        print(end=" ")
    k = k + 1
    for j in range(0, i + 1):
        print("*", end=" ")
    print("")
```

### OUTPUT


![Module 2d](https://github.com/user-attachments/assets/70233ca6-5189-4873-93a4-c31fcce6d550)

### RESULT
This program for a reversed pyramid pattern in Python using loops is successfully executed.
