You are developing a product management system for an e-commerce platform. The system has a function get_product_details(product_id: str) -> dict that takes a product ID as input and returns a dictionary with product details. The dictionary contains the following keys: 'name', 'category', 'price', and 'stock'.

The e-commerce platform has the following products:

"Wireless Mouse", Product ID: "123456", Category: "Electronics", Price: 500, Stock: 10
"Running Shoes", Product ID: "789012", Category: "Sports", Price: 600, Stock: 5
"Coffee Maker", Product ID: "345678", Category: "Home Appliances", Price: 700, Stock: 2
However, not all products are available on the platform at all times. If a product is not available, the function should raise an Exception with a message "Product not found".

Write a Python function handle_product_request(product_id: str) -> str that calls get_product_details(product_id: str) -> dict and handles any Exception that might be raised. The function should return a string message about the status of the request.

If the product is found, the function should return a message in the following format: "Product found: {name}, Category: {category}, Price: {price}, Stock: {stock}". If the product is not found, it should return the message "Product not found".

Constraints:

Product ID is a string of length 6.
The name, category are strings and price, stock are integers.
You can't install any external libraries.
Sample Input:

901234

Sample Output:

Request handled
Product not found

Explanation:

"Product not found": This message is returned when the product with the ID "901234" is not found on the platform. In this case, the get_product_details function raises an Exception with the message "Product not found". This exception is caught in the handle_product_request function and the error message is returned. This demonstrates how exception handling works in Python - when an exception occurs, instead of the program crashing, the exception is caught and handled gracefully. In this case, a meaningful message is returned to the user.
In all cases, the finally block is executed after the try and except blocks, indicating that the product request has been processed (Request handled), regardless of whether an exception was raised or not. This is a key aspect of robust software design and demonstrates the use of the finally keyword in Python exception handling.

