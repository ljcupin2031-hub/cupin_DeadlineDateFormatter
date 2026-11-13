# cupin_DeadlineDateFormatter
from datetime import datetime

e_title = input("Enter event title: ")
y = int(input("Enter year: "))
m = int(input("Enter month: "))
d = int(input("Enter day: "))

date = datetime(y, m, d)
formatted_title = e_title.upper()

print("\nFormatted Output:")
print("Event:", formatted_title)
print("Date:", date.strftime("%B %d, %Y"))
print("Year:", date.strftime("%Y"))
print("Month:", date.strftime("%B"))
print("Day:", date.strftime("%d"))
print("Weekday:", date.strftime("%A"))
