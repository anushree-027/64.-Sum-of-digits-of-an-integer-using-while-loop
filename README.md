# 64.-Sum-of-digits-of-an-integer-using-while-loop
number = int(input("Enter an integer: "))
total = 0

while number != 0:
    digit = number % 10
    total += digit
    number = number // 10

print("Sum of digits is:", total)
