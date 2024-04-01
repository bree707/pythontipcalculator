# pythontipcalculator

print("Welcome to the tip calculator!")
bill = float(input("What was the total bill? $"))
tip = int(input("How much tip would you like to give? 10, 12, or 15? "))
people = int(input("How many people to split the bill?"))
tip_as_percent = tip / 100
total_tip_amount = bill * tip_as_percent
total_bill = bill + total_tip_amount
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)
print(f"Each person should pay: ${final_amount}")

The Output in the Console should read

Welcome to the tip calculator!
What was the total bill? $153.45
How much tip would you like to give? 10, 12, or 15? 15
How many people to split the bill?5
Each person should pay: $35.29
