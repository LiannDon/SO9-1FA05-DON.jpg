import math

# Ask the user for the coordinates of the two points
x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

# Calculate the distance using the formula:
# d = sqrt((x2 - x1)^2 + (y2 - y1)^2)
distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

# Display the result
print(f"The distance between the two points is: {distance:.2f}")

# Reflection:
# Using a math library is more practical because it provides functions
# like sqrt() and pow() that make difficult calculations easier.
# Without the library, I would have to create my own way to calculate
# square roots and powers, making the program longer and more difficult.
