# Find-the-Sum-of-Digits-of-an-Integer-Using-While-Loop-Correct-Code
total = 0
number = int(input("Enter an integer: "))

while number != 0:
    digit = number % 10
    total = total + digit
    number = number // 10

print("Sum of digits is:", total)

Output:
Enter an integer: 345
Sum of digits is: 12
