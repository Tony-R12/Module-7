# 🔁 Recursion:Factorial Using Recursion in Python

## 🎯 AIM:
To Write a Python program to find the result of a! - b! using recursion.

---

## 🧠 ALGORITHM:

1. **Start**
2.Define a Recursive Factorial Function: Create a function, let's say factorial(n), that takes a non-negative integer n.

3.Establish the Base Case: Inside the factorial(n) function, include a condition where if n is 0 or 1, it returns 1. This is the stopping point for the recursion.

4.Implement the Recursive Step: If n is greater than 1, the function should return the result of n * factorial(n - 1). This breaks down the problem into smaller, manageable parts.

5.Create a Main Function: Define a new function, e.g., factorial_difference(a, b), which takes the two numbers a and b as input.

.Calculate and Return the Result: Inside factorial_difference(a, b), call the factorial function for both a and b, and then return the difference between their results (factorial(a) - factorial(b)).
7. **Stop**

---

## 💻 PROGRAM:
```
def factorial(n):
    if(n==0):
      return 1
    return(n*factorial(n-1))

a=int(input())
b=int(input())
sum=factorial(a)-factorial(b)
print(sum)
```

## OUTPUT
<img width="378" height="288" alt="image" src="https://github.com/user-attachments/assets/b3bc9930-d266-4242-a3bb-cc601194b513" />


## RESULT
Thus,the program is successfully created.

