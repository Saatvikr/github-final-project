# Simple Interest Calculator

This is a simple Python program that calculates simple interest based on user input.

## Python Code

```python
# Simple Interest Calculator

# Input principal amount, rate of interest, and time period
principal = float(input("Enter the principal amount: "))
rate = float(input("Enter the annual interest rate (as a decimal): "))
time = float(input("Enter the time period (in years): "))

# Calculate simple interest
simple_interest = (principal * rate * time)

# Display the result
print(f"Simple Interest: ${simple_interest:.2f}")
