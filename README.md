# Programe Name 
## Basic Functionality Calcultor

# Programe Working

1. This programe contain three segment 

# Segment 1
- This is Function Segment 
- - In this segment all working feature function are there
```Python
    def Addition(x,y):
  return x + y

def Subtratction(x,y):
  return x - y

def Multiplication(x,y):
  return x * y

def Division(x,y):
  if y == 0:
    return "Division by zero error!"
  else :
      return x / y

def Modulus(x,y):
  return y % x

def Square(x,y):
  return x ** y

def msg():
  return ("I hope you enjoy this .")

def eror():
  return ("Invalid input please give the correct input .")
```
# Segment 2
- This is print Statement segment    
- All statement print from there
```Python
    print ("\nDo you want to perform any calculation ")
  option = input ("Yes / no : ")
  option = option.lower()

  if option == "yes":
      print ("Welcome to World of Calculation ")
      print ("Select operation:")
      print ("1. Addittion")
      print ("2. Subtraction")
      print ("3. Multiplication")
      print ("4. Division")
      print ("5. Modulus")
      print ("6. Square")
      print ("7. Exit")
```
# Segment 3
- Calling Segment
- All the Function calling process are doing in this segment
```Python
    choice = input("Please select( 1 / 2 / 3 / 4 / 5 / 6 / 7 ) : ")
      if choice in ('1' , '2' , '3' , '4' , '5' , '6'):

          num1 = int(input("Enter first number: "))
          num2 = int(input("Enter second number: "))

          if choice == '1':
            print (num1 , "+" , num2 , "=" , Addition( num1 , num2))

          elif choice == '2':
            print (num1 , "-" , num2 , "=" , Subtratction( num1 , num2))

          elif choice == '3':
            print (num1 , "*" , num2 , "=" , Multiplication( num1 , num2))

          elif choice == '4':
            print (num1 , "/" , num2 , "=" , Division( num1 , num2))
        
          elif choice == '5':
            print(num1 , "%" , num2 , "=" , Modulus(num1 , num2))

          elif choice == '6':
            print (num1 , "**" , num2 , "=" ,Square(num1 , num2))

      elif choice == '7':
        print (msg())
        break
```

# Purpose 
- To improve My Daily Practice in Python .

# M Anas