# Exp.No:3b  
## REGEX - PATTERN MATCHING USING REGEX



### AIM  
To write a Python program that matches a string containing an `'a'` followed by **two to three `'b'` characters** using regular expressions.



### ALGORITHM

1. Begin the program.  
2. Accept a string `str1` from the user.  
3. Define the regular expression pattern as `r"[a]+b{2,3}"`.  
4. Use the `re.match()` function to check if the string `str1` matches the pattern.  
5. If a match is found, print `"Found a match!"`.  
6. If no match is found, print `"Not matched!"`.  
7. Terminate the program.


### PROGRAM

```
str1=input()
pattern=r"[a]+b{2,3}"
if re.match(pattern,str1):
    print("Found a match!")
else:
    print("Not matched!")
```
### OUTPUT
![image](https://github.com/user-attachments/assets/736f6fcc-d446-4794-8083-358ea48e6629)

### RESULT
Thus the python program for pattern matching using regular expression was implemented and executed successfully.
