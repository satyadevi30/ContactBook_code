# ContactBook_code
### Problem statement:To Store name, phone number, email, and address for each contact and to allow users to add new contacts with their details.
### Code Explanation:
#### def add_contact():
 Takes user input for a new contact's name, phone number, email, and address, and adds it to the contacts dictionary.
#### def view_contact_list():
Prints a list of contacts with their names and phone numbers
#### def search_contact():
 Takes a query (name or phone number) and searches for contacts that match the query, displaying the results.
#### def update_contact():
 Updates the details of an existing contact based on user input for the contact's name and the field to be updated (phone, email, or address).
#### def delete_contact():
 Deletes an existing contact based on user input for the contact's name.
 #### Main Loop:
####### Displays a menu of options for the user, such as adding, viewing, searching, updating, deleting contacts, or quitting the program.
####### Accepts user input and calls the corresponding function based on the user's choice.
####### The loop continues until the user chooses to quit by entering '6'.
### Conclusion:
This code is a simple implementation of a contact management system in Python. The contacts are stored in a dictionary (contacts), and the program runs in a loop until the user decides to quit. The contacts are also saved to a text file (contacts.txt) when the program exits.
Overall, this code provides a basic structure for a contact management system in Python.
