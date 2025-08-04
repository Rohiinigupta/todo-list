Console-Based To-Do List Application

This is a simple Python command-line to-do list application that allows users to add, view, and remove tasks. The tasks are saved in a text file, so they persist between program runs.

Objective
Build a basic console-based to-do list manager with task persistence using file handling.

 
 Tools Used
- Python
- VS Code / Any text editor
- Terminal / Command Prompt


 Files
- `todo.py`: Main Python file containing the application logic.
- `tasks.txt`: Text file used to store tasks persistently (auto-created on first run).


Features
- Add new tasks
- View current tasks
- Remove tasks by task number
- Tasks are saved in a text file for persistence


How to Run
1. Make sure Python is installed (`python --version`).
2. Open terminal and navigate to the project folder.
3. Run the app:

   ```bash
   python todo.py


Sample Menu
===== TO-DO LIST MENU =====
1. View Tasks
2. Add Task
3. Remove Task
4. Exit


Example Task File(tasks.txt)
Buy groceries
Finish project report
Call the doctor


Notes
Tasks are stored line-by-line in tasks.txt.
The program automatically creates tasks.txt if it doesn't exist.
Remove operation is based on the task number displayed in the list.

