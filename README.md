# program-95
# Input from user
number = int(input("Enter an integer: "))

num = number  # Keep original number
digit_sum = 0

# Loop to calculate sum of digits
while num != 0:
    digit = num % 10
    digit_sum += digit
    num = num // 10

# Print result
print("Sum of digits of", number, "is:", digit_sum)
output
Enter an integer: 1234
Sum of digits of 1234 is: 10
