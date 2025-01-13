<h1>DT_LeinaPrieur_CDOF6</h1>

# Todo List Application

A simple console-based Todo List application to manage tasks. You can add, delete, complete, and view tasks. Tasks are saved locally in a JSON file, ensuring data persistence between sessions.

## Features
- **View tasks**: Displays all tasks along with their completion status.
- **Add a task**: Allows the user to add a new task.
- **Delete a task**: Deletes a specified task.
- **Complete a task**: Marks a specified task as completed.

## Setup Instructions

Follow these steps to set up and run the Todo List application on your local machine:

### 1. Clone the Repository
```bash
git clone <https://github.com/leinapr/DT_LeinaPrieur_CDOF6.git>
cd todo_app
```

### 2. Install Dependencies
If you don't have Python installed, download and install it from [python.org](https://www.python.org/).

This project does not require any external libraries, so you can skip installing dependencies unless modifications require additional packages.

### 3. Run the Application
```bash
python todo.py
```

## Usage Instructions

1. **Run the application**: Execute `python todo.py` in your terminal.
2. **Choose an option** from the menu by entering the corresponding number:
   - `1`: View tasks
   - `2`: Add a new task
   - `3`: Delete a task
   - `4`: Mark a task as completed
   - `5`: Exit the application

## Example
```bash
Todo List Application
1. View tasks
2. Add task
3. Delete task
4. Complete task
5. Exit
Choose an option: 2
Enter task title: Buy groceries
Task added successfully!
```

## File Structure
```
todo_app/
├── todo.py             # Main application script
├── tasks.json          # Task data storage
└── README.md           # Setup and usage instructions
```

## Notes
- Ensure you have read/write permissions in the directory where the application is running, as the tasks will be saved in `tasks.json`.
- The application automatically creates `tasks.json` if it does not exist.

## License
This project is licensed under the MIT License.
