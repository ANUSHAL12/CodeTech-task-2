Overview 

The program implements a simple library management system with functionalities to manage books, magazines, and DVDs. Users can perform the following operations:

Add Items: Add new resources to the library's catalog by specifying details like title, author, category, and item type.
Checkout Items: Mark items as checked out and set a due date for their return.
Return Items: Process the return of items and calculate overdue fines based on the number of late days.
Search Items: Search for items in the catalog by title, author, or category.
Exit: Exit the program.
The system uses a command-line interface to interact with the user and employs a menu-driven approach to handle operations.

___________________________________________________________________________________________________________________________________________________________________________________________
Technologies 

Python Programming Language:

Chosen for its simplicity and readability, making it ideal for prototyping and scripting such systems.
Object-Oriented Programming (OOP):

Classes and Objects:
LibraryItem: Represents an individual library resource with attributes like title, author, and category.
Library: Manages a collection of LibraryItem objects and provides methods to perform various operations.
Encapsulation: Methods in the Library and LibraryItem classes encapsulate related functionality, ensuring modularity.
Command-Line Interface:

A simple and user-friendly way to interact with the system using text input/output.
Basic Algorithms:

Search Algorithm: Filters items in the catalog based on user-provided search criteria (title, author, or category).
Fine Calculation: Uses a simple arithmetic operation to calculate overdue fines.
Input Validation:

Ensures valid operations by checking the availability of items during checkout and return.
