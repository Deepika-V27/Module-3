# Exp.No:3c
## LIST - EVEN NUMBERS LIST


### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.



### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.



### PROGRAM

```
    l=[]
    for i in range(1,a):
        if (i%2==0):
            l.append(i)
    print(l)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/bb773640-c8ff-4a74-814c-574a8f2b6520)

### RESULT
Thus the python program for printing a list with even numbers up to n, was implemented and executed successfully.
