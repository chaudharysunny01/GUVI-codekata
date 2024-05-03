You are developing a simple calculator in Python. The calculator has a function calculate(operation: str, num1: float, num2: float) -> float that takes an operation and two numbers as input and returns the result of the operation. The operation can be one of the following: 'add', 'subtract', 'multiply', 'divide'.

However, not all operations are valid. If an invalid operation is passed, the function should raise a ValueError with a message "Invalid operation".

Also, if the operation is 'divide' and the second number is 0, the function should raise a ZeroDivisionError with a message "Cannot divide by zero".

Write a Python function handle_calculation(operation: str, num1: float, num2: float) -> str that calls calculate(operation: str, num1: float, num2: float) -> float and handles any ValueError or ZeroDivisionError that might be raised. The function should return a string message about the status of the calculation.

Constraints:

num1 and num2 are floats.
You can't install any external libraries.
Sample Input:

add, 1.0, 2.0

Sample Output:

Result: 3.0

Explanation:

The result of the operation is displayed in the message.

