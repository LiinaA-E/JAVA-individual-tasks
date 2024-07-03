## JAVA-individual-tasks

# 15.05.2024 Individual Task TicTacToe

Create a simple tic-tac-toe game. Depending on your skills and knowledge.
Game grid should be 3x3. It should be possible for the user to put values in the grid by typing row number and column number.

Easy: Ask user for row and column and write in the two dimensional array a value "1" in the correct place.
Check whether or not the row chosen by user contains all 1.
If all elements in row contain 1, then let player know they won.

Medium: Ask for row and column and write in the two dimensional array a value "1" or "2" in the correct place, depending on which players turn it is. Switch the turn after every move.
Check whether or not the row chosen by user contains all 1, or all 2.
Check whether or not the column chosen by user contains all 1, or all 2.
(1 represents X, 2 represents O, 0 represents empty)

Hard: A regular tic-tac-toe, check diagonals as well. Instead of 1 and 0, use X and O (2D array should be of char type.)
After every move make sure the playing field is not full and make it draw, if it is full.

# 29.05.24 Individual Task Book Manager

Develop a simple book management application with ArrayList.
User should be able to add a book to ArrayList.
User should be able to remove a book from ArrayList.

Easy: Work with String in ArrayList. All the actions should be available for user.

Medium: Work with String User should be able to repeat all the actions infinitely.

Hard: Create a Book class and work with Book object to the ArrayList.

# 13.06.2024 Individual Task Cheese Shop

Develop a program that contains multiple classes.

Choose one of the topics.

Easy: Cheese shop

Should contain these classes.

Cheese 

CheeseShop - gives access for the shop owner to add/remove different cheeses, gives access for the customer to buy different cheeses, remove cheese from cart, should be possible to get all the cheeses from the cart or available cheeses in the store

Main - User UI, accesses CheeseService and CheeseShop to buy or to add different cheeses.


Medium: same as easy, but add 2 more classes

CheeseService - gives access for the shop owner to add different cheeses (should remove this functionality from CheeseShop)

Customer - contains money the customer has, contains the items the customer owns. Whenever the customer buys something, money is reduced. If customer doesn't have any money left, then notify the user about it.



Hard: Same as medium, but save all the data in JSON.txt file. Should be able to save all the data in JSON and when opening the program again, it should save all the information.
