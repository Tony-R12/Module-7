# 📐 Taylor Series Using Recursion in Python

## 🎯 AIM:
To write a Python program to evaluate a **Taylor Series** using **recursion**, where values of `x` and `n` are taken from the user.

## 🧠 ALGORITHM:

1. **Start**
2. Create variables `x` and `n`
3. Get values for `x` and `n` from the user
4. Define a recursive function `series(x, n)`
   - **Base case:** If `n == 0`, return 1
   - **Recursive case:** Return `x**n / n + series(x, n-1)`
5. Print the result
6. **Stop**

## 💻 PROGRAM:
```
\def fun(x,n):
    if(n==0):
        return 1 
    else:
        return (((x**n)/n)+fun(x,n-1))
x=int(input())
n=int(input())
print(fun(x,n))
```

## OUTPUT
<img width="591" height="270" alt="image" src="https://github.com/user-attachments/assets/32b58783-1168-4da5-abb2-83264b08283c" />


## RESULT
Thus,the program is successfully created.
