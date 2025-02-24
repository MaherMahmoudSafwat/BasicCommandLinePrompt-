C# Command Line Project - Basic Shell Emulator This project is a command-line application built in C# using OOP principles to simulate basic shell commands. 
The application allows users to interact with a simple terminal-like interface and execute 10 commands:

touch [filename] – Creates a new file. mkdir [dirname] – Creates a new directory. reset – Resets the terminal state. clear – Clears the console screen. cd [path] – 
Changes the current directory. history – Displays previously executed commands. date – Prints the current date and time. rm [filename/dirname] – Deletes a file or directory. list – 
Lists files and directories in the current folder. echo [message] – Prints a message to the console.

How It Works :

The program continuously reads user input. It parses the command and calls the corresponding method. Results are displayed in the console. History is stored for later retrieval.
