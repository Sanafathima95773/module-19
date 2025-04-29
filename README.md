# Ex 1A RECURSIVE FUNCTION
### 1A Reverse a String  ###
### Aim:
The aim of this program is to create a recursive function that takes a string as input and returns its reverse. The function should utilize recursion to break down the string into smaller parts, progressively reversing the string until the entire string is reversed.
### Algorithm:
```
Step 1: Define a function that takes a string as input.
Step 2: Check if the length of the string is 0 or 1 (base case).
  - If yes, return the string itself.
Step 3: Otherwise, call the same function recursively with the substring that excludes the first character.
Step 4: Append the first character to the result of the recursive call.
Step 5: Return the final result.
```
### code:
```
def reverse(s):
    if len(s)==0:
        return s
    else:
        return s[-1]+reverse(s[:-1])
s=input()
print(reverse(s))
```

### output
![image](https://github.com/user-attachments/assets/520986b9-b68a-46c5-8cc8-02a4ab135b8d)

###   Result
Thus the program is executed successfully
