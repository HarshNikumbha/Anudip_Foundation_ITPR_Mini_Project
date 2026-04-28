# Contact Book System

A simple command-line Contact Book implemented in Python. It provides basic CRUD
operations (create, read, update, delete) via an interactive menu. Contacts are
kept in memory while the program runs.

**Features**

- **Add**: Prompt and store a new contact (name, phone, email, address).
- **View**: List all saved contacts in a readable format.
- **Search**: Find a contact by name and display details.
- **Update**: Update phone, email, or address for an existing contact.
- **Delete**: Remove a contact by name.

**Requirements**

- Python 3.7 or newer

**Usage**

1. Open a terminal in the project folder.
2. Run the program:

```bash
python contact_book.py
```

3. Use the interactive menu to add, view, search, update, or delete contacts.

Example session:

```text
$ python contact_book.py
===== Contact Book System =====
1. Add Contact
2. View Contacts
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit
Enter your choice: 1
Enter contact name: Alice
Enter phone number: 123-456-7890
Enter email address: alice@example.com
Enter address: 123 Maple St
Contact added successfully!
```

**Notes & Next steps**

- Currently contacts are stored only in memory; exiting the program will lose
  all data. To persist contacts between runs consider adding saving/loading to
  a file (JSON/CSV) or using a lightweight database (SQLite).
- Consider adding input validation, duplicate-name handling, and unit tests.

**Files**

- Main script: [contact_book.py](contact_book.py#L1-L200)

**Contributing**

- Feel free to open issues or submit pull requests to add features or fixes.

**License**

- No license defined. Add a `LICENSE` file if you intend to publish or share.
