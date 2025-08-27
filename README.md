# Assigmenti2
# task 01
def factorial(n):
    fact = 1
    for i in range(1, n + 1):
        fact *= i
    return fact

num = int(input("Enter a number :"))
result = factorial(num)
print("The factorial of", num, "is:", result)


# task 02
import math

num = float(input("Enter a number: "))

square_root = math.sqrt(num)
natural_log = math.log(num)        # log base e
sine_value = math.sin(num)         # in radians

print("Square root of", num, "is:", square_root)
print("Natural logarithm of", num, "is:", natural_log)
print("Sine of", num, "radians is:", sine_value)
