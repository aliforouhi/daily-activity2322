# daily_update.p
import random

print("Daily GitHub activity - Day 22")

numbers = [random.randint(1, 100) for _ in range(5)]
average = sum(numbers) / len(numbers)

print("Today's random numbers:", numbers)
print("Average value:", round(average, 2))
