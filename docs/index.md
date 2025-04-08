# --- Part 1: Convert Celsius to Fahrenheit ---

# Declare a Celsius temperature
celtemp = 30

# Convert Celsius to Fahrenheit
fahtemp = (celtemp * 9 / 5) + 32

# Print the Fahrenheit temperature
print("Temperature in Fahrenheit:", fahtemp)

# --- Part 2: Cash Register Simulation ---

# Accept the price of the item
price = float(input("Enter the price of the item (example 7.48): "))

# Accept the amount of cash given
cash_given = float(input("Enter the amount of cash given (example 10.00): "))

# Calculate the change
change = cash_given - price

# Print the change due
