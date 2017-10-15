# todo-firebase-app
A todo app built with vanila js &amp; firebase.

### Demo
https://my-app-87dbe.firebaseapp.com/

## Features
- Input validation
  - Minimum 5 chars to have "Add" button enabled
  - "Add" button disabled by default
  - "Add" button disabled and input is cleared when "Add" button gets clicked
  - Color indication of input validness
- Display all todos from firebase database when app is loaded
- Add a new todo to firebase database is input is valid and user clicks on "Add" button
- Remove a todo from firebase database when a user clicks on it in the list
- Listen for changes in the database 'child_added', 'chiled_changed', 'chiled_removed' and call appropriate methods to handle todos in the list on the app.
