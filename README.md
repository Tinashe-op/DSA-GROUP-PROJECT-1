git reposistory link - https://github.com/Tinashe-op/DSA-GROUP-PROJECT-1


Phonebook Application
General Description
This application is a simple command-line phonebook manager. It allows users to perform various operations on contact entries, including adding, searching, displaying, deleting, updating, and sorting contacts. The program uses two parallel lists to store names and phone numbers, providing a basic but functional contact management system.
Modules and Functions
Main Program Flow

main(): The entry point of the application. It displays a menu and handles user input to execute various functions in a loop until the user chooses to exit.

User Interface

displayMenu(): Prints the menu options for the user to choose from.
getUserChoice(): Validates and retrieves the user's menu selection.

Contact Management

insertContact()

Role: Adds a new contact to the phonebook.
Functionality: Prompts the user for a name and number, then adds these to the respective lists.


searchContact()

Role: Searches for a contact by phone number.
Functionality: Asks for a number to search, then iterates through the list to find a match.


displayAllContacts()

Role: Shows all contacts in the phonebook.
Functionality: Iterates through the lists and prints each contact's information.


deleteContact()

Role: Removes a contact from the phonebook.
Functionality: Searches for a contact by name or number and removes it if found.


updateContact()

Role: Modifies an existing contact's information.
Functionality: Finds a contact by name or number, then allows the user to enter new information.



Sorting Functions

sortContacts()

Role: Main sorting function that allows choosing between name and number sorting.
Functionality: Calls either sortByName() or sortByNumber() based on user choice.


sortByName()

Role: Sorts contacts alphabetically by name.
Functionality: Creates entries of name-number pairs, sorts them, and updates the lists.


sortByNumber()

Role: Sorts contacts in ascending order of phone numbers.
Functionality: Similar to sortByName(), but sorts based on phone numbers.



Data Structure
The application uses two parallel lists:

names: Stores contact names
numbers: Stores corresponding phone numbers

These lists are manipulated together to maintain the relationship between names and numbers.
User Interaction
The program interacts with the user through console input/output. It repeatedly displays a menu and prompts for user input to execute various functions until the user chooses to exit.
Error Handling
Basic error handling is implemented, particularly for input validation. The program handles cases such as invalid menu choices and non-existent contacts gracefully.
