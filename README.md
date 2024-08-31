# OOP-2-Task-1
OOP-2   Task-1
#  Statements of Conditional
print('Conditional Statements Example:')
print('Provide two numbers: ')
num1, num2 = input().split()
num1, num2 = int(num1), int(num2)
if num1 > num2:
    print(num1, 'is greater than', num2)
elif num1 < num2:
    print(num1, 'is smaller than', num2)
else:
    print(num1, 'is equal to', num2)

print('\n')
#  Examples of Loop
print('Using Break in Loop:')
names_list = ["Tom", "Jerry", "Spike", "Tyke"]
for name in names_list:
    print(name, end=' ')
    if name == "Spike":
        break

print('\n')

print('Using Continue in Loop:')
names_list = ["Tom", "Jerry", "Tyke", "Butch"]
for name in names_list:
    if name == "Tyke":
        continue
    print(name, end=' ')

print('\n')

print('While Loop Example:')
limit = int(input('Enter a number: '))
current = 1
print('Counting from 1 to', limit, ':')
while current <= limit:
    print(current, end=' ')
    current += 1

print('\n')
# Multiple  from User  Input
print('Multiple Inputs from User:')
print('Please enter two numbers: ')
number1, number2 = input().split()
print('Entered Numbers:', number1, number2)
print('Sum:', int(number1) + int(number2))

# Examples of Range Function 
print('Range Function Example:')
display_range(5, 16)

print('Numbers from 50 to 80:')
display_range(50, 81)

print('Even Numbers from 50 to 80:')
display_range(50, 81, 2)

print('Numbers from 90 to 60 in reverse:')
display_range(90, 59, -3)

print('\n')

# Example of Mathematical Operations
def perform_math_operations(a, b):
    addition = a + b
    subtraction = a - b
    multiplication = a * b
    modulus = a % b
    exponentiation = a ** b
    print('Addition:', addition)
    print('Subtraction:', subtraction)
    print('Multiplication:', multiplication)
    print('Modulus:', modulus)
    print('Exponentiation:', exponentiation)
    print()

    # Definitions of Function 
def check_parity(num):
    if num % 2 == 0:
        print("Even")
    else:
        print("Odd")

def display_range(start, end, step=1):
    total_sum = 0
    for num in range(start, end, step):
        total_sum += num
        print(num, end=' ')
    print('Total Sum:', total_sum)
    print()

    
