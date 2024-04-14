# assesment

## Components

### Table: The table displays a list of users. Each row in the table represents a single user and includes the following columns:
* ID (readonly)
* Username
* Email
* Enabled (checkbox)
* Actions (dropdown menu with "Edit" and "Delete" options)

### New User Section: This section allows administrators to create new users. It includes the following fields:
* Username: Text field for entering a username.
* Display Name: Text field for entering a display name.
* Phone: Text field for entering a phone number (optional).
* Email: Text field for entering an email address.
* User Roles: Dropdown menu for selecting user roles (multiple selections may be allowed).
* Enabled: Checkbox for enabling/disabling the user account.
* Buttons:
* * Save User: Saves the new user information or saves changes to an existing user.
* * Hide Disabled Users: Option to hide disabled users from the table.
Behavior

### Table:
The table is initially sorted by username in ascending order.
Clicking on a row in the table selects the corresponding user and populates the "New User" section with the user's details.
The "Enabled" checkbox can be used to enable or disable a user account.
Selecting "Edit" from the "Actions" dropdown menu populates the "New User" section with the user's details for editing.
Selecting "Delete" from the "Actions" dropdown menu prompts the user for confirmation before deleting the user.
New User Section:
Fields are initially empty when creating a new user.
When editing an existing user, the fields are pre-populated with the user's current information.
The "Save User" button saves the new user information or saves changes to an existing user.
Error messages are displayed below the corresponding field if invalid data is entered (e.g., username already exists, invalid email format).
Buttons:
Clicking "Save User" validates the entered information and saves the user data. If successful, a confirmation message is displayed, and the table is updated to reflect the changes.
Clicking "Hide Disabled Users" toggles the visibility of disabled users in the table.
Initial State

The table displays a list of all users, sorted by username.
The "New User" section is empty.
The "Hide Disabled Users" checkbox is not selected (disabled users are visible).
User Roles

Only users with administrator privileges should be able to access the user management screen.
