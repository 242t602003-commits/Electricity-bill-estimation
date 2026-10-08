# Current Measurement.py

import random
import time

print("===================================")
print("       CURRENT MEASUREMENT")
print("===================================")

# Number of readings
num_readings = 10

current_readings = []

for i in range(num_readings):

    # Simulated current reading in Amperes
    current = random.uniform(2, 10)

    current_readings.append(current)

    print(f"Reading {i + 1}: {current:.2f} A")

    time.sleep(1)

# Calculate average current
average_current = sum(current_readings) / len(current_readings)

print("\n===================================")
print(f"Average Current = {average_current:.2f} A")
print("===================================")

# Current status
if average_current < 2:
    print("Status: LOW CURRENT")
elif average_current > 8:
    print("Status: HIGH CURRENT")
else:
    print("Status: NORMAL CURRENT")
