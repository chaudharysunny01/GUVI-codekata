Design a Python program that uses hierarchical inheritance to model electronic devices. There are two types of electronic devices: Mobiles and Laptops. Both Mobiles and Laptops have a brand name and a price. However, a Mobile also has a screen size, while a Laptop has a screen resolution.

Create classes to represent both types of devices and use hierarchical inheritance to avoid code duplication. Write a method in each class to print the details of the device.

Sample Input:

Samsung Galaxy S21, 799.99, 6.2 inches
Dell XPS 13, 999.99, 1920 x 1080

Sample Output:

Mobile: Samsung Galaxy S21, Price: $799.99, Screen Size: 6.2 inches
Laptop: Dell XPS 13, Price: $999.99, Screen Resolution: 1920 x 1080

Explanation:

In the sample output, each line represents the details of an electronic device:

The first line is the details of a mobile. It's a Samsung Galaxy S21 with a price of $799.99 and a screen size of 6.2 inches.
The second line is the details of a laptop. It's a Dell XPS 13 with a price of $999.99 and a screen resolution of 1920 x 1080.
These details are printed by calling the print_details() method of each device object. The method is defined in each class and prints the details specific to that device.

This is an example of hierarchical inheritance, where the Mobile and Laptop classes inherit from a common base class (ElectronicDevice). The base class defines properties and methods common to all electronic devices (like name and price), while the derived classes add properties and methods specific to mobiles and laptops (like screen_size and screen_resolution).

Constraints:

The name of the mobile or laptop is a string and can contain any printable ASCII characters.
The price of the mobile or laptop is a float and can be any positive number.
The screen size of the mobile is a string and can contain any printable ASCII characters.
The screen resolution of the laptop is a string and can contain any printable ASCII characters.