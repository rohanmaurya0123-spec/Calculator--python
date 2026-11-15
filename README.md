''' Calculator--python
This is calculator by using python programme that conduct simple calculation'''

while True:
    print("\n======= PYTHON CALCULATORM ========")
    a = int(input("Enter your first number: "))
    operator = input("Enter :'+,-,*,/:'"   )
    b = int(input("Enter your second number: "))

    try:
        if operator == '+':
            print("The value is ",a + b )
        elif operator == "-":
            print("The value is",a -b)
        elif operator == '*':
            print("The value is", a * b)
        elif operator == '/':
            print("The value is", a/b)
    except ValueError:
        print("please enter valid number")
