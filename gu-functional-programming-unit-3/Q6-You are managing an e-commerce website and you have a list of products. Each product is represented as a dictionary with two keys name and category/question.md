You are managing an e-commerce website and you have a list of products. Each product is represented as a dictionary with two keys: 'name' and 'category'. You want to create a list of all products that belong to the category 'Electronics'. Write a Python function electronics_products(products) that takes a list of products and returns a list of tuples where each tuple contains the product name and the category. Use a tuple comprehension to create the list.

Input:

products: a list of dictionaries. Each dictionary represents a product and has two keys: 'name' (a string) and 'category' (a string).
Output:

The function should return a list of tuples where each tuple contains a product name and the category.
Sample Input:

[{'name': 'Product 1', 'category': 'Books'}, {'name': 'Product 2', 'category': 'Electronics'}, {'name': 'Product 3', 'category': 'Electronics'}]

Sample Output:

[('Product 2', 'Electronics'), ('Product 3', 'Electronics')]

Explanation:

The tuple comprehension generates a new list containing tuples of the names and categories of all products that belong to the 'Electronics' category. It does this by iterating over each product in the products list and checking if the product's category is 'Electronics'. If it is, a tuple containing the product's name and category is added to the new list. This demonstrates how tuple comprehensions can be used to create new lists based on existing lists in Python. In the context of managing an e-commerce website, this can be useful to quickly find all products that belong to a certain category.