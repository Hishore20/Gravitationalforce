# Gravitationalforce
Write a Python Program to Find the Gravitational Force Acting Between Two Objects
Logic Test Case 1

Input (stdin)
1000000

500000

20

Expected Output

0.08 N
Logic Test Case 2

Input (stdin)
90000000

700000

20

Expected Output

10.51 N



a=int(input())
b=int(input())
c=int(input())
d=6.67*(10**-11)
e=(a*b*d)/(c**2)
print('%.2f N'%e)

