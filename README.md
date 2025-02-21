# Python Average Calculator with ZeroDivisionError Handling

This repository contains a Python function designed to calculate the average of a list of numbers. It includes robust error handling to prevent `ZeroDivisionError` when an empty list is provided as input. 

## Function: `calculate_average(numbers)`

The `calculate_average` function takes a list of numbers as input and returns their average. If the input list is empty, it gracefully returns 0 to avoid division by zero errors.

## Usage

The function can be used like this:
```python
 numbers = [10, 20, 30, 40, 50]
average = calculate_average(numbers)
print(f"The average is: {average}")

 numbers = []
average = calculate_average(numbers)
print(f"The average is: {average}") # Output: 0
```