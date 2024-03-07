AirBnB Clone
This is an AirBnB clone project developed as part of a software engineering course.

Command Interpreter
The command interpreter is a Python-based tool that allows users to interact with the AirBnB clone system through a command-line interface (CLI). It provides various functionalities to manage objects within the system, such as creating, updating, deleting, and displaying information about instances of classes.

How to Start
To start the command interpreter, follow these steps:

Clone the repository to your local machine.
Navigate to the directory containing the project files.
Run the command ./console.py to start the command interpreter.
How to Use
Once the command interpreter is running, you can use the following commands:

help: Display available commands and their descriptions.
quit: Exit the command interpreter.
create <class_name>: Create a new instance of the specified class.
show <class_name> <id>: Display information about the specified instance.
destroy <class_name> <id>: Delete the specified instance.
all [class_name]: Display information about all instances or all instances of a specific class.
update <class_name> <id> <attribute_name> "<attribute_value>": Update the specified attribute of the instance.
Examples
Here are some examples of how to use the command interpreter:

To create a new user instance: create User
To display information about a specific user: show User 1234-5678
To update the name of a listing: update Place 8765-4321 name "New Listing"
