# Basic Calculator Program

def calculator():
    print("Welcome to the Basic Calculator!")
    print("Available operations: + for addition, - for subtraction, * for multiplication, / for division")
    

        # Get input from the user
num1 = float(input("10"))
num2 = float(input("5 "))
operation = input("+,/,*,-"  )
        
        # Perform the operation and display the result
if operation == "+":
        result = num1 + num2
print(f"{num1} + {num2} = {result}")
operation == "-"
result = num1 - num2
print(f"{num1} - {num2} = {result}")
operation == "*"
result = num1 * num2
print(f"{num1} * {num2} = {result}")
operation == "/"
if num2 != 0:
                result = num1 / num2
                print(f"{num1} / {num2} = {result}")
            

