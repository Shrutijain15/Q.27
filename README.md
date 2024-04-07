# Q.27
# Example list
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Divisor
divisor = 3

# Use list comprehension to filter out the numbers that are divisible by the divisor
divisible_numbers = [num for num in numbers if num % divisor == 0]

# Print the list of numbers that are divisible by the divisor
print("Numbers divisible by", divisor, "are:", divisible_numbers)
