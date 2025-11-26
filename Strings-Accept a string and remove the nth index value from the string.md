# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(str): 
l=len(str) 
a=""
n=int(input())
for i in range(0,l): 
if i==n:
a=a+"" 
else:
a=a+str[i] 
print(a)
```

## Output

<img width="766" height="173" alt="516719063-a14e7571-37a4-4883-b27e-d7c3bba6141f" src="https://github.com/user-attachments/assets/36ba16a1-77f0-4ab6-a461-903bea527c4c" />

## Result
Thus the program has been successfully executed
