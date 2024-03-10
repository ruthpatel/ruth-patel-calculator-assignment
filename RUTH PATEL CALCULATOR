history = []

def add(x, y):
    result = x+y
    print("Result : {0} + {1} = {2}".format(x, y, result))
    history.append("{0} + {1} = {2}".format(x, y, result))
    
    
def sub(x, y):
    result = x-y
    print("Result : {0} - {1} = {2}".format(x, y, result))
    history.append("{0} + {1} = {2}".format(x, y, result))
    
def mul(x, y):
    result = x*y
    print("Result : {0} * {1} = {2}".format(x, y, result))
    history.append("{0} * {1} = {2}".format(x, y, result))
    
def div(x, y):
    if y==0:
        print("Cannot divide by zero")
        
    else:
        result = x/y
        print("Result : {0} / {1} = {2}".format(x, y, result))
        history.append("{0} / {1} = {2}".format(x, y, result))
        
def display_history():
    for i in history:
        print(i)
        
while 1:
    print("Calculator")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")
    print("5. Show History")
    print("6. Exit")
    
    n = int(input("Enter your choice (1-6): "))
    
    if n==6:
        break
    
    elif n==5:
        display_history()
    
    elif n>6:
        print("Invalid choice.Please enter a number between 1 and 6.")
    
    else:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        
        if n==1:
            add(a, b)
            
        elif n==2:
            sub(a, b)
        
        elif n==3:
            mul(a, b)
            
        elif n==4:
            div(a, b) 