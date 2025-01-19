# python-assignment

1/
A namespace in Python is a container that holds a set of identifiers (variable 
names, function names, etc.) and maps them to corresponding objects. It ensures 
that names are unique and avoids naming conflicts. Python has different types of 
namespaces: 
 Local Namespace: Includes names defined within a function. 
 Global Namespace: Includes names defined at the top level of a script or 
module. 
 Built-in Namespace: Contains built-in functions and objects. 
Example: 
x = 10 # Global namespace 
def my_function(): 
 y = 20 # Local namespace 
 print("Local y:", y) 
my_function() 
print("Global x:", x) 


2/
def reverse_string(input_string): 
 return input_string[::-1] 
# Example usage 
original = "Hello" 
reversed_string = reverse_string(original) 
print("Original:", original) 
print("Reversed:", reversed_string)

assignment 2

1/
Source Code: 
def calculate_average(a=0, b=0, c=0): 
 return (a + b + c) / 3 
# Example usage 
print("Average of default values:", calculate_average()) # All numbers 
are 0 
print("Average of 10, 20, 30:", calculate_average(10, 20, 30)) 



2/ 
To import a specific function from a Python module, use the from ... 
import ... syntax. This approach avoids importing the entire module and 
allows you to directly use the function. 
Example: 
# Importing only the sqrt function from the math module 
from math import sqrt 
# Example usage 
number = 16 
result = sqrt(number) 
print(f"The square root of {number} is {result}")
