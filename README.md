HYDRATE MATE – Mini Project

⭐ Title

Hydrate Mate – Daily Water Intake Tracker



⭐ Aim

To calculate a user’s recommended daily water intake based on their weight and activity level, and provide an hourly hydration plan.


⭐ Objectives

To collect user input (weight & activity level).

To calculate the total water required for the day.

To provide a clear output in liters.

To give an hourly drinking schedule for better hydration.



⭐ Programming Language Used

Python

⭐ Code

# HYDRATE MATE – Daily Water Tracker

print("---- HYDRATE MATE ----")

# Aim: To calculate and remind the user of their daily water intake requirement.

# Input
weight = float(input("Enter your weight (in kg): "))
activity = input("Are you active today? (yes/no): ").lower()

# Process
# Basic formula → 35 ml per kg
water_needed = weight * 35   # in ml

# Add extra water for active days
if activity == "yes":
    water_needed += 500   # extra ml

liters = water_needed / 1000

# Output
print("\n---- DAILY WATER GOAL ----")
print(f"Your recommended water intake is: {liters:.2f} liters")

# Extra Output: Hourly reminder plan
hours = 12
per_hour = liters / hours

print(f"Drink about {per_hour:.2f} liters every hour to stay hydrated!")



⭐ Sample Input / Output

Input:

Enter your weight (in kg): 55  
Are you active today? yes

Output:

---- DAILY WATER GOAL ----
Your recommended water intake is: 2.43 liters
Drink about 0.20 liters every hour to stay hydrated!


⭐ Conclusion

Hydrate Mate helps users understand their daily water requirements and provides a simple hourly routine to maintain hydration, promoting a healthier lifestyle.


