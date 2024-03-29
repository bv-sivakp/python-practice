# Introduction

Python is a popular programming language that lets you work quickly
and integrate systems more effectively.

## Used for
- Web and UI Development
  - Popular libraries (django, Flask) 
- Software  
- Big data and mathematics
- System scripting
- System Administration
- Data Science*
- Machine Learning*
  - Face recognition, voice recognition 
- Artificial Intelligence*
- Data collections like Web Scraping
  - web crawlers
- Automation
    - DevOps tasks
    - Monitoring infra
    - Automatic Backups and cleaning tasks (house keeping)
    - General tasks
- Mobile, Gaming and Desktop Development (less likely use cases)
- Popular libraries
    - Data anlysis and Data visualization and artficial intelligence

## Popular Modules 
 - PyTorch
 - Pandas
 - NumPy
 - TensorFlow
 - theano
 - NLTK (Natural Language Analyses)
 - Keras
 - plotly
 - matplotlib

## Module Repository
 - Pypi ( Python package Index)
 - Package is a collection of python modules
 - pip install (pip is a package manager for python)
 - 
## Features
 - Cross-platform
 - Complex mathematics
 - Rapid prototyping
 - Run on interpreter system
 - Procedural/functional/object-oriented
 - Easy learning curve with simple syntax
 - Large ecosystem
    - many libraries
    - large community
 - Many Libraries and Large Community
 - Flexible
    - You're not limited to language specifics (syntax, datatypes)
    - Extend widely
    - Multi Purpose language

## Versions
 - Python 3 (Most recent)
    -   py --version

## Editors
 - Command line mode
    - py (starts the editor)
    - exit()
 - Text Editor
 - VS Code
 - Thonny
 - Pycharm
 - Netbeans or Eclipse

## Sytax
 - Newlines are used for the EOL
 - Uses indentation, using whitespaces to define scope

## Installation
 - Windows (https://www.python.org/downloads/)
 - Linux
    - add-apt-repository ppa:deadsnakes/ppa
    - apt-get install -y default-jre
    - apt install -y python3.7
    - apt-get install -y python3-pip python-dev build-essential
    - pip3 install --upgrade pip

## Variables
 - x=10 (creates a variable when you assign a value to it)
 - Variable names are case sensitive
 - Variable names
    - Can start with letter or underscore or alphanumeric
    - Can be camel,pascal, snake casing

## Comments
  - single and multi line comment #
  - Multi-line
  - ```sh
      """ (ptyhon ignores string literals that are not assigned to a variable)
          this is
          multi line comment
      """
    ```
## Assignment and casting and type
  - x=5
  - y=str(3)
  - z="Hello" (strings can be defined in single or double quotes)
  - print(type(x))

## Multiple variable assignation
- x, y = "Hello", "World"
- x=y="Hello"
- countries=["India","Australia", "England"]
- x, y, z = countries

## Global variables
- x="Hello"
  def func1():
    print("x value is " + x)
   func1()
- def func1():
  global x  (To make vairable as global) 
  x = "foo"
  print("x value is " + x)
  
## Build in Datatypes
- Basic types: str, bool 
- Sequence types: tuple, list, range 
- Numerics: int, float, complex
- Mapping: dict
- Set Types: set,frozenset
- Binary: bytes, bytearray, memoryview

| Collection | Ordered |Changable | Duplicates | 
| ------ | ------ | ------ | ------ |
| Lists | Yes | Yes | Yes |
| Tuples | Yes | No | Yes |
| Sets | No | No | No |
| Dictionaries | Yes | Yes | No |
