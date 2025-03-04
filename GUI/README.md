# ToDo App with GUI

## Summary
This Python script is a graphical ToDo application built using the `FreeSimpleGUI` library. It allows users to manage their tasks through a user-friendly graphical interface. Users can add, edit, and complete tasks, as well as exit the application. The tasks are stored in a text file (`tasks.txt`), ensuring persistence across sessions. The application also includes a real-time clock and clear error handling for invalid inputs.

## Features
- **Graphical User Interface (GUI)**: The application uses `FreeSimpleGUI` to provide a clean and intuitive interface for managing tasks.
- **Add Tasks**: Users can add tasks by typing the task description in the input field and clicking the "Add" button.
- **Edit Tasks**: Users can edit a selected task by clicking the "Edit" button after selecting a task from the list and entering a new description.
- **Complete Tasks**: Users can mark a task as completed by selecting it from the list and clicking the "Complete" button.
- **Exit Application**: Users can exit the application by clicking the "Exit" button or closing the window.
- **Real-Time Clock**: The application displays a real-time clock at the top of the window.
- **Task Persistence**: Tasks are stored in a text file (`tasks.txt`), ensuring that tasks are saved between sessions.
- **Error Handling**: The application provides pop-up messages for invalid inputs, such as attempting to edit or complete a task without selecting one.

## How to Use
1. Run the script in a Python environment.
2. Use the input field to enter a new task and click "Add" to add it to the list.
3. To edit a task, select it from the list, enter a new description in the input field, and click "Edit".
4. To mark a task as completed, select it from the list and click "Complete".
5. To exit the application, click "Exit" or close the window.

## Requirements
- Python 3.x
- The `FreeSimpleGUI` library (`pip install FreeSimpleGUI`).
- A `functions.py` module with the following functions:
  - `getTasks()`: Reads tasks from `tasks.txt` and returns them as a list.
  - `addTasks(tasks)`: Writes the list of tasks to `tasks.txt`.

## Running the Program
To run the program, simply execute the script in your Python environment:
```bash
python todogui.py
```
