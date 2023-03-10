Airbnb Clone

Description

This is the first phase of the Airbnb Clone: the console. This repository holds a command interpreter and classes (i.e. BaseModel class and several other classes that inherit from it: Amenity, City, State, Place, Review), and a command interpreter. The command interpreter, like a shell, can be activated, take in user input, and perform certain tasks to manipulate the object instances.

How to Use Command Interpreter
|-----------------------------|
|COMMANDS |SAMPLE USAGE | FUNCTIONALITY|
|--------|--------------|--------------|
|help | help | displays all commands available |
|create | create <class> | creates new object (ex. a new User, Place) |
| update | User.update('123', {'name' : 'Greg/_n/_Mel'}) | updates attribute of an object |
| destroy | User.destroy('123') | destroys specified object|
| show | User.show('123') | retrieve an object from a file, a database |
| all | User.all() | display all objects in class |
| count | User.count() | returns count of objects in specified class |
| quit | quit | exits |
