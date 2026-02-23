#1. users input + type conversions

monthly_income = int(input("Enter your monthly income: "))

food = int(input("Enter amount for food: "))

rent = int(input("Enter amount for rent: "))

transport = float(input("Enter amonut for Transport: "))

other_expenses = float(input("Enter amount for other expenses: "))

#Calculations
total_expenses = food + rent + transport + other_expenses 

remaining_balance = monthly_income  - total_expenses

print("\n--- Summary ---")
print("total expenses:", total_expenses )
print("remaining balance:", remaining_balance )

#3 Conditions
if remaining_balance > 0:
  print("status: You are within budget")
elif remaining_balance == 0:
   print("status: Your budget is balanced")
else:
   print("status: You are over budget")

#4 loops
months = int(input("\nHow many months do you want to simulate? "))
for month in range(1, months + 1):
   print("\nMonth", month)
   print("Remaining balance:", remaining_balance )

   if remaining_balance < 0:
      print("Warning: Debt increasing")

#logical operators:
if monthly_income > total_expenses and remaining_balance >= 1000:
   print("You have good financial control")
