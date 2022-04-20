# Tic-Tac-Toe-using-Python
What is Tic Tac Toe game?
Tic Tac Toe is a 2 player game where each player has a symbol (either X or O) and plays alternately to mark their symbol on a 3×3 grid.

If any player gets their(X or 0) symbol consecutively 3 times in a row, column or diagonal then that player is the winner. So, in total, we have 8 winning conditions: 3 for the rows, 3 for the columns, and 2 for the diagonals. Isn’t it interesting!

So, we will be coding it in Python using Tkinter for the interface.


Tkinter‘ is one of the known in-built libraries of Python. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with tkinter is the fastest and easiest way to create GUI applications. All you need to do is perform the following steps:

We first need to import the tkinter module.

Since, we also have to display the results, we should use messagebox widget. As MessageBox Widget is used to display the message boxes in the python applications. Hence to use this, we have to import messagebox.

Using * after import means we have imported all the methods, variables of the tkinter library.

Now, let’s create the GUI application main window i.e. game window.

Here, we will create a Tk widget and assigned it to a variable root. And title() used to set the title of the window.

Let’s assign two variables: click and count as well. Initialise ‘click’ to ‘True’ and ‘count’ to ‘0’. According to our logic, if click=True that means ‘X’ is clicking and if it is False that means it’s time for ‘0’ to click, while the count variable will check how many turns have been played, and after every turn, the count variable will be incremented by 1.



Algorithm or Logic behind Tic Tac Toe:-
This is how it works. Whenever a player clicks on the button, we need to add symbols over it. The press() function does exactly the same. The parameters passed are num, r, c. 
