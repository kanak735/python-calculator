# python-calculator
a simple calculator using python


print("---CALCULATOR---")

num1 = float(input("enter first number here:"))
num2 = float(input("enter second number here:"))

print("press 1 for addition")
print("press 2 for subtraction")
print("press 3 for multiplication")
print("press 4 for division")


choice = int(input("enter your choice from 1-4:"))

if choice == 1:
    print("The addition of given two numbers is",num1 + num2)


elif choice == 2:
    print("The subtraction of given two numbers is",num1 - num2)


elif choice == 3:
    print("The multiplication of given two numbers is",num1 * num2)


else:
    print("Invalid Input")

print("excution successful")

