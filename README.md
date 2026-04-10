Project Description
This is a full-stack web application built using the Flask framework. The system allows users to manage their personal contacts through a user-friendly interface. It supports all major CRUD (Create, Read, Update, Delete) operations and stores data in a dynamic in-memory list for quick performance.

Features
Create: Add new contacts with names, phone numbers, and email addresses.

Read: View a list of all saved contacts in a clean, organized table.

Update: Edit existing contact details with pre-filled forms.

Delete: Remove contacts from the list with a confirmation prompt.

Search (Bonus): Quickly find contacts by name or phone number using the search bar.

Responsive UI: Styled with CSS for better readability and navigation.

Tech Stack
Backend: Python 3.x, Flask

Frontend: HTML5, CSS3 (Jinja2 Templates)

Version Control: Git & GitHub

 Project Structure
Plaintext
contact_management_system/
│
├── app.py              # Main Flask application logic & routing
├── static/
│   └── style.css       # Basic UI styling
├── templates/
│   ├── base.html       # Shared layout (Navbar, Boilerplate)
│   ├── index.html      # Home page (Contact List & Search)
│   ├── add_contact.html# Form to create new contacts
│   └── edit_contact.html# Form to update existing contacts
└── README.md           # Documentation
