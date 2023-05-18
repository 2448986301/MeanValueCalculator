def calculate_average(numbers):
    if not numbers:
        return None
    total = sum(numbers)
    average = total / len(numbers)
    return average

# 示例用法
my_numbers = [1, 2, 3, 4, 5]
result = calculate_average(my_numbers)
print("平均值:", result)
