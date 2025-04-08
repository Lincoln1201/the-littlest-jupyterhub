 Declare a Celsius temperature
celtemp = 30

# Convert Celsius to Fahrenheit
fahtemp = (celtemp / 5) * 9 + 32

# Print the Fahrenheit temperature
print(f"Temperature in Fahrenheit: {fahtemp}")
# Accept the price of the item
price = float(input("Enter the price of the item (e.g., 7.48): "))

# Accept the amount of cash given
cash_given = float(input("Enter the cash given (e.g., 10.00): "))

# Calculate the change
change = cash_given - price

# Print the change due
print(f"Change due: {change:.2f}")
