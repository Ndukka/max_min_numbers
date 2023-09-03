# max_min_numbers

So someone sent me this message.

Write a Python program that requests 5 integer values from the user. It then prints the maximum and minimum values entered. Your program should handle ties properly: for example, if the user enters: 2, 4, 2, 3, 3 the program should report 2 as the minimum and 4 as the maximum.

There are different ways to go about it but I chose the simple route. 

What I will be doing here is to choose an empty space, then ask the user to input an integer. I also have to catch exceptions, just incase the user inputs a letter or anything else that can crash the program.  Secondly, we have to change that integer to a string, this way, we can be able to check for the maximum and minimum. Lastly, we also have to make sure that the user is able to input just one number. We should throw an error just incase he chooses more than one numbers. 

