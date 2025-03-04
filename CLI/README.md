# ToDo App

## Summary
This Python script is a simple command-line ToDo application that allows users to manage their tasks. Users can add, show, edit, and complete tasks, as well as exit the application. The tasks are stored in a text file (`task.txt`), ensuring persistence across sessions. The program provides a user-friendly interface with clear prompts and error handling for invalid inputs.

## Features
- **Add Tasks**: Users can add tasks to their ToDo list by typing `add` followed by the task description.
- **Show Tasks**: Users can view all tasks in their list by typing `show`.
- **Edit Tasks**: Users can edit a specific task by typing `edit` followed by the task number and providing a new description.
- **Complete Tasks**: Users can mark a task as completed by typing `complete` followed by the task number. The task is then removed from the list.
- **Exit Application**: Users can exit the application by typing `exit`.
- **Error Handling**: The program handles invalid inputs gracefully, providing clear error messages for incorrect commands or task numbers.
- **Task Persistence**: Tasks are stored in a text file (`task.txt`), ensuring that tasks are saved between sessions.
- **User-Friendly Interface**: The program provides clear prompts and feedback for each action.

## How to Use
1. Run the script in a Python environment.
2. Follow the prompts to add, show, edit, complete, or exit tasks.
3. Use the following commands:
   - **Add a task**: Type `add` followed by the task description (e.g., `add Buy groceries`).
   - **Show tasks**: Type `show` to view all tasks.
   - **Edit a task**: Type `edit` followed by the task number and provide a new description (e.g., `edit 1`).
   - **Complete a task**: Type `complete` followed by the task number (e.g., `complete 1`).
   - **Exit the application**: Type `exit`.

## Requirements
- Python 3.x
- A `functions.py` module with the following functions:
  - `getTasks()`: Reads tasks from `task.txt` and returns them as a list.
  - `addTasks(actions, filename)`: Writes the list of tasks to `task.txt`.

## Running the Program
To run the program, simply execute the script in your Python environment:
```bash
python todocli.py
```
