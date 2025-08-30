# Experiment-4
## ARMSTRONG NUMBER 
# Aim: 
 Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program
```
num = int(input("Enter a number: "))
num_str = str(num)
power = len(num_str)
armstrong_sum = sum(int(digit) ** power for digit in num_str)
if num == armstrong_sum:
    print(num, "is an Armstrong number.")
else:
    print(num, "is not an Armstrong number.")
```
# Output
1.
<img width="447" height="105" alt="image" src="https://github.com/user-attachments/assets/40ea64f2-c272-4c9e-bee7-13fb4a179d6c" />

2.
<img width="437" height="113" alt="image" src="https://github.com/user-attachments/assets/fb9ec98a-a2ac-46a5-ab8d-2cdf2e6b8af4" />

# Result
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
