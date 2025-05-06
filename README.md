# Accept-any-positive-integer-and-display-the-range-of-number-from-1-to-that-positive-integer 
#  Positive Integer Range Display Program

This Python program accepts **any positive number** from the user and displays all numbers from **1 up to that number** using a `while` loop. If the input is zero or negative, it prints an error message.

---

##  Program Logic

- Accept user input as a **float** (e.g., 5.0, 10.2).
- Print' The input value is invalid' if the value is less than or equal to 0.
- The program accepts decimal values like 5.9 but prints only whole numbers up to that value.
- You can modify the code to use int() instead of float() if you want strictly integer input.
- If it's positive, display numbers from 1 to the entered value (as an integer range).
- Use a `while` loop to iterate through the range.

---

# Code

```python
# Accepting input from the users
n = float(input("Enter the value:"))

# Logic used 
if n <= 0:
    print('The input value is invalid')
else:
    if n > 0:
        print("Input the number within the range of {}".format(n))
        i = 1
        while n >= i:
            print("\t {}".format(i))
            i = i + 1
print("The program is over")
