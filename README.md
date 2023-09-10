def factorial(n):
    return 1 if (n==1 or n==0)
  else n * factorial(n-1);
 
#Enter input
n = int(input("Enter input number : "))
 
print("The factorial of",n,"is",factorial(n))
def CheckLeap(Year):  
  # Checking if the given year is leap year  
  if((Year % 400 == 0) or  
     (Year % 100 != 0) and  
     (Year % 4 == 0)):   
    print("Given Year is a leap Year");  
  # Else it is not a leap year  
  else:  
    print ("Given Year is not a leap Year")  
# Taking an input year from user  
Year = int(input("Enter the number: "))  
# Printing result  
CheckLeap(Year)
