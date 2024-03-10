Description
The first step towards building a full web application, this repository contains a back-end console which will manage the coming projects: HTML/CSS templating, database storage, API and front-end integration.

Usage
The hbnb console works in both interactive and non-interactive mode. In interactive mode, a prompt is printed and it waits for input from the user.

$ ./console.py
(hbnb)

In non-interactive mode, a command can be piped:

$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$

Command	Description:

quit::	Quits the console
EOF::	Quits the console
help::	Displays help page
create <class>::	Creates a new instance of a given class with a unique ID and saves it to a JSON file
show <class> <id>::	Prints the string representation of a class instance based on the class name and ID
destroy <class> <id>::	Deletes an instance based on the class name and id and saves it to a JSON file
all::	Prints all string representation of all instances based or not on the class name
update::	Updates an instance based on the class name and id by adding or updating attribute and saves changes to a JSON file
