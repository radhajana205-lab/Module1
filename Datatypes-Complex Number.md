# 🧮 Datatypes-Complex Number Creation in Python
## NAME: JANARTHANI R
## REF NO: 25017541
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
a=int(input())

b=int(input())

x=complex(a,b)

print("complex Number:",x)

print("Real Part:",x.real)

print("Imaginary Part:",x.imag)
## Output
Enter real part:3

Enter imaginary part:4

Complex Number:(3+4j)

Real Part:3.0

Imaginary Part:4.0
## Result
Thus, the Python program to read two integers, create a complex number, and display its real and imaginary parts was written and executed successfully.
