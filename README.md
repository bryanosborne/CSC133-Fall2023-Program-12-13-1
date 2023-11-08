# CSC133-Fall2023-Program-12-13-1 - Keeping Order

Wizard of Oz Solutions received an important request to develop a program in Python that can read a file of user ID’s to determine if a specific user ID is present in the file.

The program should be designed to prompt a user for the user ID they are looking for, check to see if it is in the user ID file, and print a message letting the user know if it is there or not.

Ensure the code is properly commented before you submit the code.  

It is critical that you create a clear algorithm to solve this problem. Create the algorithm FIRST and use it to create comments for your source code.

Since Wizard of Oz Solutions is an advocate of modular code and code reuse, the program will need to be written using a function that loads the file line by line into a list for the program’s main to process.

Care should also be given to perform user input validation, i.e., userIDs have specific requirements (see next slide). Invalid userIDs should be rejected.

You will need to create an input file for the program. Each line in the file should contain only one userID. Although the final userID file may have hundreds of userIDS, the input file used for testing file should contain at 10-15 userIDs. 

UserID’s for the system in question must have 8 or more characters and may consist of uppercase and/or lowercase letters, as well as numbers, but no special characters.

In order for a userID to be a “match” it must match EXACTLY what the user entered, i.e.,
JOsborne1 DOES NOT MATCH josborne1
