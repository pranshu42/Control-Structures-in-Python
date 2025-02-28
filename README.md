# Control-Structures-in-Python
TASK1 DETAILS:-
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


