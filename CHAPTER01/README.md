# CHAPTER 01: The Python Data Model

1. Python's Consistency: Python is known for its consistency, which allows users to make informed and correct guesses about new features.

2. Difference from Other Object-Oriented Languages: Python may appear different to those who have learned other object-oriented languages, as it uses len(collection) instead of collection.len().

3. Python Data Model: The Python Data Model is the key to understanding Pythonic code. It formalizes the interfaces of language building blocks, such as sequences, functions, iterators, coroutines, classes, and context managers.

4. Framework Description: The data model describes Python as a framework, specifying how different elements interact and work together.

5. Special Methods: Python uses special methods (denoted by double underscores before and after the method name) to perform basic object operations. For example, __getitem__ is called when using the syntax obj[key].

6. Usage of Special Methods: When creating new classes or leveraging the Python Data Model, the interpreter invokes special methods for performing operations, often triggered by specific syntax. For instance, my_collection[key] results in a call to my_collection.__getitem__(key).

7. We implement special methods when we want our objects to support and interact with fundamental language constructs such as:

• Collections

• Attribute access

• Iteration (including asynchronous iteration using async for)

• Operator overloading

• Function and method invocation

• String representation and formatting

• Asynchronous programming using await

• Object creation and destruction

• Managed contexts using the with or async with statements

---
[Additional Info]: *** Magic and Dunder ***
* "Magic method" is slang for "special method."
* "Dunder-getitem" is a term learned from Steve Holden, meaning "double underscore before and after" for special methods. Special methods are also known as "dunder methods."
* The Python Language Reference warns about the use of 
"\__*__" names without explicit documentation.
---

## 1.1 A Pythonic Card Deck
* Check out at ""

