# Todo List with Filtering Functionality

This project is a simple **Todo List application** built with **React.js**. The application allows users to:

- Add new todos with a task description and username.
- Mark todos as completed or not completed.
- Filter the list of todos by their completion status (all, completed, or not completed).
- Delete individual todos.

The application is built using **React** and **Babel** loaded via **CDN links**, making it easy to run in the browser without additional setup.

## Features

1. **Add Todo**: Users can add a new todo by entering a task description and their name. Upon submission, the new todo is added to the list.
2. **Display Todos**: Todos are displayed in a table format, showing the serial number, todo title, username, and status (completed or not completed).
3. **Delete Todo**: Each todo has a "Delete" button that allows the user to remove the todo from the list.
4. **Mark as Completed**: Users can mark a todo as completed or not completed by clicking the status button in the table.
5. **Filtering**: Users can filter the todos based on their completion status using a dropdown. The options are:
   - All: Show all todos.
   - Completed: Show only the completed todos.
   - Not Completed: Show only the not completed todos.

## Usage

### How to Run

1. Create an HTML file (e.g., `index.html`) and paste the provided code into the file.
2. Open the HTML file in any modern web browser to view the todo list application.

Alternatively, use the following steps to integrate this code into any existing React project.

### Code Breakdown

1. **TodoInput Component**:

   - This component contains two input fields: one for entering the todo description and one for the user's name.
   - It also has a submit button to add the new todo to the list.

2. **TodoDisplay Component**:

   - This component displays the list of todos in a table.
   - Each todo shows the serial number, todo title, user name, and its completion status.
   - There are buttons to toggle the todo status (completed/not completed) and to delete the todo.

3. **App Component**:
   - This is the main component that contains the state and logic for managing todos, filtering, and handling actions like adding, deleting, and updating todos.
   - It maintains the list of todos and handles state changes.

### File Structure

```plaintext
index.html
README.md
```
