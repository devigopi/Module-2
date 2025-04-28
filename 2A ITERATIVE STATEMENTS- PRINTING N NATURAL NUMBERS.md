# Exp. No: 2a  
## ITERATIVE STATEMENTS – 1 to n Odd numbers in reverse order

###  Aim
To create a Python Program to print 1 to n Odd numbers in reverse order.

---

###  Algorithm

1. Begin the program.
2. Input a positive integer n.
3.Check if n is even:
  If yes, decrease n by 1 to make it odd.
4.Initialize a loop variable i with the value of n.
5.Loop while i > 0:
  Print the value of i.
  Decrease i by 2 (to move to the next smaller odd number).
6.Terminate the program.

---

### 🧾 Program

```python
#Reg.NO-212223020028
#Name- Tharani devi.G
#Write your Code here
n=int(input())

for i in range(n,0,-1):
    if i%2!=0:
        print(i)
```
### OUTPUT
![Module 2B](https://github.com/user-attachments/assets/3852e53a-0b6d-419b-9202-fd62d894b4d6)

### RESULT
```
This program for  1 to n Odd numbers in reverse order is successfully executed.

```

