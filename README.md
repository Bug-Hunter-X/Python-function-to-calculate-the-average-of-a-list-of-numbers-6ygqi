# Python Average Calculator

This repository contains a Python function designed to calculate the average of a list of numbers. The function includes error handling for empty input lists.

## Function: `calculate_average(numbers)`

This function takes a list of numbers as input and returns their average.  If the input list is empty, it returns 0 to avoid a `ZeroDivisionError`.

### Usage

```python
from calculate_average import calculate_average

my_numbers = [10, 20, 30, 40, 50]
average = calculate_average(my_numbers)
print(f"The average is: {average}")

my_empty_list = []
average = calculate_average(my_empty_list)
print(f"The average is: {average}") # Output: 0
```