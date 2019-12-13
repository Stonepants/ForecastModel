# ForecastModel

# The objective of the program was to make it possible and easy for a single person to determine when and what to purchase since the recipient did not yet have a proper overview of the item they had in stock. Furthermore the program can optimise the purchase allocation within the given item (since, for most products you had to order in large amounts eg. 1000 of a black thirt across sizes) 

# Simply run the macros is the Command Sheet one by one, and the program will extract new data from the SQL server the computer is hooked up to. It will create a view of the current stock holding for the choosen products and use a liner regressing from the previous sales on the choosen items to determine a forecast for the products.
# In the Solver sheet you are then able to extract the products that the program estimates to fall below the requires stock threshold and you are able to use the solver to optimize the purchase strategy given the estimated stock in the future.

# Hopefully the program will prevent that the recipient will ever run out of stock on the products they dont want to run out of as well as smooth their current stockholding over time, such that they are able save money on keeping too much stock. 
