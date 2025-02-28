# Control-Structures-in-Python
# TASK1 DETAILS:-
This is a simple Python program that checks whether the number entered by the user is even or odd.

1. Input from the User:

n = int(input("Enter a number: "))
input(): The input() function is used to take input from the user. By default, input() returns the value as a string, so we need to convert it into an integer.
int(): This function converts the input string to an integer. So, n will store the user's input as an integer.
2. Checking if the Number is Even or Odd:

if n % 2 == 0:
% (Modulo operator): The modulo operator returns the remainder when one number is divided by another.
The condition n % 2 == 0 checks whether the remainder when n is divided by 2 is 0.
If n % 2 == 0, it means that the number is divisible by 2 without leaving a remainder, i.e., it is an even number.
3. If the Number is Even:

print(n, "is an even number")
If the condition n % 2 == 0 is true (i.e., the number is even), this line is executed, and the program will print the message "<number> is an even number".
4. If the Number is Odd:
python
Copy
else:
    print(n, "is an odd number")
else: If the condition n % 2 == 0 is false (i.e., the number is not divisible by 2), then the else block is executed. This means the number is odd.
The program prints "<number> is an odd number".
Example:
Example 1:

Enter a number: 4
4 is an even number
Example 2:


Enter a number: 7
7 is an odd number
Summary:
The program uses the modulo operator to check if the number is divisible by 2.
If the remainder is 0 (n % 2 == 0), the number is even; otherwise, it's odd.

# TASK2 DETAILS:-
This program calculates the sum of integers from 1 to 50 using a for loop.

1. Initialization of the Variable:

total_sum = 0
Here, the variable total_sum is initialized to 0. This variable will be used to store the cumulative sum of integers as the loop iterates.
2. The For Loop:

for i in range(1, 51):
range(1, 51): The range() function generates a sequence of numbers. In this case, it generates numbers starting from 1 up to (but not including) 51. So, it will generate the numbers from 1 to 50.
range(start, stop) generates numbers starting from the start value and up to, but not including, the stop value.
For Loop: The for i in range(1, 51) means that the loop will run 50 times, with the value of i changing from 1 to 50 during each iteration. In each iteration, i will take a new value from the range (1, 2, 3, ..., 50).
3. Updating the Total Sum:
   
   
total_sum += i
This line updates the value of total_sum in each iteration. The += operator is a shorthand for total_sum = total_sum + i.
During the first iteration, i will be 1, so total_sum becomes 0 + 1 = 1.
In the next iteration, i will be 2, so total_sum becomes 1 + 2 = 3, and so on.
This continues until the loop reaches i = 50, and total_sum will store the sum of all integers from 1 to 50.
4. Printing the Final Result:
   
   
print("The sum of integers from 1 to 50 is:", total_sum)
After the loop finishes, the program prints the result stored in total_sum, which is the sum of all integers from 1 to 50.
The print() function outputs the message along with the value of total_sum.
Output:
The program will print:


The sum of integers from 1 to 50 is: 1275
Summary of the Process:
Initialize total_sum to 0.
Loop through numbers from 1 to 50 using the range() function.
Add each number to total_sum during every iteration.
After the loop finishes, print the final sum.
The program efficiently calculates the sum of integers from 1 to 50 and displays it.





