# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:
```
def fun(n):
    if (n >0):
        fun(n - 2)
        print(n, end=" ")
 
x = int(input())
if(x%2==0):
    fun(x)
else:
    fun(x-1)
```

## OUTPUT
<img width="968" height="262" alt="image" src="https://github.com/user-attachments/assets/a6be4bf6-a1f7-4caf-b686-e3baf51756f8" />


## RESULT
Thus,ths program is successfully created.
