# aljunaidtech_tasks
# Task 1: Print Personal Information
name = "John Doe"
gender = "Male"
age = 25
address = "123 Main Street, City, Country"
degree = "Bachelor of Science in Computer Science"
dob = "January 1, 2000"
contact = "123-456-7890"

print("--- Personal Information ---")
print(f"Name: {name}")
print(f"Gender: {gender}")
print(f"Age: {age}")
print(f"Address: {address}")
print(f"Degree: {degree}")
print(f"Date of Birth: {dob}")
print(f"Contact: {contact}\n")

# Task 2: Swapping Variables with Type Casting
a = 5  # Integer
b = 10.5  # Float

print("--- Before Swapping ---")
print(f"a = {a}, b = {b}")

a, b = float(a), int(b)  # Type casting while swapping
a, b = b, a  # Swapping values

print("--- After Swapping ---")
print(f"a = {a}, b = {b}\n")

# Task 3: Declare Variables with Different Data Types
integer_var = 10  # Integer
float_var = 20.5  # Float
string_var = "Hello, Python!"  # String
boolean_var = True  # Boolean
list_var = [1, 2, 3, 4, 5]  # List
tuple_var = (10, 20, 30)  # Tuple
dict_var = {"name": "Alice", "age": 30}  # Dictionary

print("--- Variables with Data Types ---")
print(f"integer_var ({type(integer_var)}): {integer_var}")
print(f"float_var ({type(float_var)}): {float_var}")
print(f"string_var ({type(string_var)}): {string_var}")
print(f"boolean_var ({type(boolean_var)}): {boolean_var}")
print(f"list_var ({type(list_var)}): {list_var}")
print(f"tuple_var ({type(tuple_var)}): {tuple_var}")
print(f"dict_var ({type(dict_var)}): {dict_var}")




# Task 1: Arithmetic Operations
a = 10
b = 5

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Modulo:", a % b)

# Task 2: Comparison Operators
print("\nComparison Operators:")
print("a > b:", a > b)
print("a < b:", a < b)
print("a == b:", a == b)
print("a != b:", a != b)
print("a >= b:", a >= b)
print("a <= b:", a <= b)

# Task 3: Assignment Operators
print("\nAssignment Operators:")
x = 20
print("Initial x:", x)
x += 5
print("After x += 5:", x)
x -= 3
print("After x -= 3:", x)
x *= 2
print("After x *= 2:", x)
x /= 4
print("After x /= 4:", x)
x %= 3
print("After x %= 3:", x)

# Task 4: Logical Operators
print("\nLogical Operators:")
bool1 = True
bool2 = False

print("bool1 and bool2:", bool1 and bool2)
print("bool1 or bool2:", bool1 or bool2)
print("not bool1:", not bool1)
