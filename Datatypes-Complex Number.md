# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
Add Code Here:
```
# Read real and imaginary parts
a = int(input("Enter real part: "))
b = int(input("Enter imaginary part: "))

# Create complex number
x = complex(a, b)

# Display results
print("Complex Number:", x)
print("Real Part:", x.real)
print("Imaginary Part:", x.imag)
```

## Output:
```
Enter real part: 5
Enter imaginary part: 3
Complex Number: (5+3j)
Real Part: 5.0
Imaginary Part: 3.0
```

## Result:
The python program is executed successfully.
