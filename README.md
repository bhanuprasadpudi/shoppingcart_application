# shoppingcart_application
Shopping Cart Application

Overview:
The application provides an functionality of adding items into cart and also whishlist the items which we want buy next time instead of adding to cart. It manages items in the cart and a wishlist, providing methods for adding, updating, and calculating totals.
Here’s a concise overview Python code:
	.The code defines two classes: Item and ShoppingCart.
	.The Item class represents an item with a name and price, and it has a custom string representation.
	.The ShoppingCart class manages items in the cart and a wishlist, providing methods for adding, updating, and calculating totals.
	.The program offers a menu-driven interface for users to interact with the shopping cart.


Description:

Python code defines two classes: Item and ShoppingCart. Let’s break down what each class does:

=>Item Class:
	.The Item class represents an individual item with a name and a price.
	.It has an __init__ method that initializes the name and price attributes.
	.The __str__ method returns a formatted string representation of the item, including its name and price.

=>ShoppingCart Class:
	.The ShoppingCart class manages a collection of items and a wishlist.
	.It has the following methods:
		.add(item): Adds an item to the cart.
		.update(name, price): Updates the price of an existing item in the cart.
		.wishlist_add(item): Adds an item to the wishlist.
		.wishlistitems(): Prints the items in the wishlist.
		.cart_wishlist(name): Moves an item from the wishlist to the cart.
		.total(): Calculates the total price of items in the cart.
		.whishlist_total(): Calculates the total price of items in the wishlist.
		.remove_items(name): Removes an item from the cart.
		.remove_whislist_items(name): Removes an item from the wishlist.
		.__str__: Returns a string representation of the items in the cart.

=>Purpose:
	.Manages a collection of items in the cart and a wishlist.
	.Offers methods for adding items, updating prices, listing items, calculating totals, and more.
	.Provides a menu-driven interface for users to interact with the shopping cart.
	.Overall, the code aims to create a basic shopping cart system that allows users to perform various operations related to items and their prices.

toolsused:
	.jupyter notebook(anaconda)

Conclusion:
	The provided Python code defines two classes: Item and ShoppingCart. The Item class represents individual items with names and prices, while the ShoppingCart class manages items in the cart and a wishlist. Users can interact with the shopping cart through a menu-driven interface, performing actions like adding items, updating prices, listing items, and calculating totals.
