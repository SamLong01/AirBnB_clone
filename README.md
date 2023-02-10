# AirBnB clone - The Console

![Image Link] (<https://raw.githubusercontent.com/coding-max/hbtn_config/main/assets/hbnb.png>)

---

## Table of Content

* Description
* Purpose
* Requirements
* Execution

---

### Description

![Image Link] (<https://stenwire.github.io/AirBnB_clone/media/concept.png>)

---

### Purpose

The purpose of this project is to understand how to:

* create a Python package
* create a command interpreter using the cmd module
* serialize and deserialize a Class
* write and read a JSON file
* manage datetime
* use *args and **kwargs
* handle named arguments in a function

---

### Requirements

#### Python Scripts

* All the files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
* All the files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory.
* The code should use the pycodestyle (version 2.8.*)
* All the files must be executable
* All the modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All the classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All the functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')

#### Python Unit Tests

* All the files should end with a new line
* All the test files should be inside a folder tests
* You have to use the unittest module
* All the test files should be python files (extension: .py)
* All the test files and folders should start by test_
* Your file organization in the tests folder should be the same as your project
* All the tests should be executed by using this command: python3 -m unittest discover tests
* All the modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All the classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All the functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')

---

### Execution

The shell should work like this in interactive mode:

```Terminal
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb)
(hbnb)
(hbnb) quit
$
```

But also in non-interactive mode: (like the Shell project in C):

```Terminal
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

All tests should also pass in non-interactive mode:

```Terminals
echo "python3 -m unittest discover tests" | bash
```
