def add(a,b):
    return a+b

def subtract(a,b):
    return a-b

def multiply(a,b):
    return a*b

def divide(a,b):
    if b == 0:
        return "Error: Cannot divide by zero"
    return a/b
print('Simple Calculator')

a = float(input('Enter the first number: '))
operator = input('Enter the operator(+,-,*,/):')
b = float(input('Enter the second number: '))



if operator == '+':
  print('Result:', add(a,b))
elif operator == '-':
  print('Result:',subtract(a-b))
elif operator == '*':
  print('Result:',multiply(a,b))
elif operator == '/':
  print('Result:', divide(a,b))
else:
  print('Invalid operator')