# Caesar_Cipher_and_File_Search
This Python application combines a Caesar Cipher encryption tool with a file search functionality, implemented using the Tkinter GUI library. It's designed to demonstrate the Caesar Cipher encryption technique and to provide a practical example of file operations and threading in Python.
Caesar Cipher Encryption: Allows the user to enter a text message and encrypts it using the Caesar Cipher method, displaying all possible permutations of the cipher (shifting by 1 to 25).
File Search and Encrypt: Provides a feature to search for a specific file in a given directory and apply the Caesar Cipher encryption to the file's content.
Graphical User Interface: Built using Tkinter, the application offers a user-friendly interface to interact with the features.
Caesar Cipher: The user inputs a message in a text field.
On clicking the 'Toate Permutatile' button, the application generates all permutations of the Caesar Cipher for the given message and displays them.
File Search and Encryption:
The user inputs the filename to search and the application looks for this file in the specified directory.
Threading is used to divide the search operation into multiple segments for faster processing.
If the file is found, the application reads its content, applies the Caesar Cipher encryption, and then overwrites the file with the encrypted content.
