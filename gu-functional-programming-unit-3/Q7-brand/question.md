You are managing an e-commerce website and you have a list of products. Each product is represented as a dictionary with three keys: 'name', 'category', and 'brand'. You want to create a set of all unique brands present in your product list. Write a Python function unique_brands(products) that takes a list of products and returns a set of unique brands. Use a set comprehension to create the set.

Input:

products: a list of dictionaries. Each dictionary represents a product and has three keys: 'name' (a string), 'category' (a string), and 'brand' (a string).
Output:

The function should return a set of unique brands.
Sample Input:

[{'name': 'Product 1', 'category': 'Books', 'brand': 'Brand A'}, {'name': 'Product 2', 'category': 'Electronics', 'brand': 'Brand B'}, {'name': 'Product 3', 'category': 'Electronics', 'brand': 'Brand B'}]

Sample Output:

['Brand A', 'Brand B']

Explanation:

The set comprehension generates a new set containing unique brands of all products. It does this by iterating over each product in the products list and adding the product's brand to the new set. Since sets in Python only contain unique elements, any duplicate brands are automatically removed. This demonstrates how set comprehensions can be used to create new sets based on existing lists in Python. In the context of managing an e-commerce website, this can be useful to quickly find all unique product brands.",