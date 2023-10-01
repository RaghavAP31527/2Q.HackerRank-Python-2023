Explain

n = int(input()): This line of code takes an integer input from the user and stores it in the variable n.

if (n % 2) != 0:: This line checks if n is odd. The % operator calculates the remainder when n is divided by 2, so (n % 2) will be 0 if n is even and non-zero if n is odd.

print('Weird'): If n is odd, i.e., (n % 2) != 0, it prints 'Weird' because odd numbers are considered weird according to the conditions specified in the problem.

If n is even (i.e., (n % 2) == 0), the code enters an else block to further evaluate n based on the following conditions:

if 2 <= n <= 5:: This condition checks if n is in the range between 2 and 5 (inclusive). If it is, it prints 'Not Weird'. This implies that even numbers in this range are considered "Not Weird."

elif 6 <= n <= 20:: This condition checks if n is in the range between 6 and 20 (inclusive). If it is, it prints 'Weird'. This implies that even numbers in this range are considered "Weird."

elif n > 20:: If n is greater than 20 and even, it prints 'Not Weird'. This implies that even numbers greater than 20 are considered "Not Weird."
