# AirBnB Clone

## Description

This project is an implementation of a command-line interpreter for managing AirBnB-like objects. It allows users to create, update, delete, and display various objects such as users, places, and amenities.

## Command Interpreter

The command interpreter provides a user-friendly interface to interact with the AirBnB_clone project. Here's how to start and use it:

### How to Start

To start the command interpreter, simply run the following command:

```bash
./console.py


How to Use

Once the command interpreter is started, you can use the following commands:

    create: Create a new instance of a specified class.
    show: Display information about a specific instance.
    destroy: Delete a specific instance.
    all: Display information about all instances or all instances of a specified class.
    update: Update attributes of a specific instance.

For a complete list of available commands and their usage, you can use the help command within the interpreter.
Examples

Here are some examples of how to use the command interpreter:

****************************************************************************************


(hbnb) create User
e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1
(hbnb) show User e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1
[User] (e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1) {'id': 'e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1', 'created_at': '2024-02-14T12:00:00', 'updated_at': '2024-02-14T12:00:00'}
(hbnb) all
["[User] (e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1) {'id': 'e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1', 'created_at': '2024-02-14T12:00:00', 'updated_at': '2024-02-14T12:00:00'}"]
(hbnb) update User e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1 first_name "John"
(hbnb) show User e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1
[User] (e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1) {'id': 'e7c3b418-dba2-4fbd-95ed-c80baa2cc6c1', 'created_at': '2024-02-14T12:00:00', 'updated_at': '2024-02-14T12:00:00', 'first_name': 'John'}



****************************************************************************************