# Experiment No: 5 – SEB-Maximum of Three Numbers

## AIM  
To write a Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator).

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the largest number:  
   - If `num1` is larger than or equal to both `num2` and `num3`, then `num1` is the maximum.  
   - Else, if `num2` is larger than or equal to both `num1` and `num3`, then `num2` is the maximum.  
   - Otherwise, `num3` is the maximum.  
4. Print the maximum value along with the input numbers in the format:  
   `"The maximum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```

num1 = int(input())
num2 = int(input())
num3 = int(input())

max_num = num1 if (num1 >= num2 and num1 >= num3) else num2 if (num2 >= num1 and num2 >= num3) else num3

print(f"The maximum of {num1}, {num2}, {num3} is {max_num}")
```

## OUTPUT

![image](https://github.com/user-attachments/assets/d93272f4-befb-4722-be6d-744541cfe4db)

## RESULT

Thus the Python program to find the maximum between three integer numbers using a conditional expression (Ternary operator) was implemented successfully.

