# calculator-in-python
def add(x , y):
 return x + y

def subtract(x , y):
 return x - y

def divide(x , y):
 return x / y
 
def multiply(x , y):
 return x * y

print("Select operation: ")
print("1. Addition")
print("2. Subtraction")
print("3. Division")
print("4. Multiplication")

while True:
   choice = input("Enter your choice(1,2,3,4): ")
   
   if choice in ('1' , '2' , '3', '4' ):
     num = float(input(" Enter first number: "))
     num = float(input(" Enter second number: "))
     
     if choice == '1':
       print("Addition of two numbers are: ", num1,"+", num2, "=",  add(num1,num2))
     elif choice == '2':
       print("Subtraction of two numbers are: ", num1,"-", num2, "=",  subtract(num1,num2))
     elif choice == '3':
       print("Multiplication of two numbers are: ", num1,"*", num2, "=",  multiply(num1,num2))
     elif choice == '4':
       print("Division of two numbers are: ", num1,"/", num2, "=",  divide(num1,num2))
     break:
  else:
     print("Invalid Input")
    
    
    
   
