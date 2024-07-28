# Assistant Bot for Address Book Management

This assistant bot is designed to manage your address book. With its help you can add, edit and delete contacts, manage phone numbers and birthdays.

## Description

The assistant-bot provides the following functions:
- Adding and editing contacts
- Adding and deleting phone numbers
- Adding birthdays
- Deleting contacts and clearing the entire address book
- Searching and displaying contact information
- Display upcoming birthdays

### Commands

    - hello : Just a greeting.
    - add <name> <phone> : Adds a new contact.
    - mod <name> <new_phone>: Updates an existing contact.
    - del <name> Deletes an existing contact.
    - phone <name>: Displays the contact's phone number.
    - all: Displays all contacts.
    - clear: Deletes all contacts.  
    - add-b <name> <DD.MM.YYYY> : Adds a birthday date
    - show-b <name> : Shows a birthday date
    - b-days : displays a list of birthdays for the next 7 days
    - exit or close: Exits the program.

## Usage
assistant_bot/python main.py
