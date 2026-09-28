# BUG: Missing colon at the end of the while statement - added : to fix it
# BUG: < 5 stops the loop at 4 so 5 is never added, giving 10 instead of 15 - changed to <= 5 to fix it
while count <= 5:
    total = total + count
    count = count + 1
 
# BUG: Cannot join a string and an integer with + - changed to an f-string to fix it
print(f"Sum of 1 to 5 is: {total}")
 
