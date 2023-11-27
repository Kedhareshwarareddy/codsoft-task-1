# codsoft-task-1
# README: To Do List (TASK 1)

## Author: KEDHARESHWARA SUBBA REDDY S

## Batch:(NOVEMBER A13)

## Domain: PYTHON Programming

## Aim

The aim of this project is to build a To-Do List Application

## Description

This application allows users to add tasks, mark tasks as completed, update task descriptions,add priority to tasks and remove tasks from the list. This has been implemented in a graphical user interface (GUI).

## Libraries Used

The following important libraries were used for this project:

- tkinter

- ##Description


1. **Task Entry Section:**
   - The application allows users to input task details, including the task description, priority level, and due date.
   - Entry fields include:
     - Task description (`task_entry`)
     - Priority level (`priority_entry`)
     - Due date (`due_date_entry`)

2. **Add Task Button:**
   - Clicking the "Add Task" button (`add_button`) adds a new task to the list.
   - The task details are displayed in a Listbox (`task_list`), and the corresponding details are appended to the `self.tasks` list.

3. **Task List:**
   - The Listbox displays the list of tasks with their descriptions, priorities, due dates, and statuses.
   - Users can select a task from the list for further actions.

4. **Mark Complete Button:**
   - Clicking the "Mark Complete" button (`mark_complete_button`) changes the status of the selected task from "Pending" to "Completed."

5. **Update Task Button:**
   - Clicking the "Update Task" button (`update_button`) allows users to modify the details of the selected task in the list.
   - The modified task details are updated in both the Listbox and the `self.tasks` list.

6. **Remove Task Button:**
   - Clicking the "Remove Task" button (`remove_button`) removes the selected task from the list.

7. **Error Handling:**
   - The application provides error messages using `messagebox.showerror` in case of incomplete or incorrect user inputs.

8. **Clear Entries Function:**
   - The `clear_entries` function is called to clear the input fields (`task_entry`, `priority_entry`, and `due_date_entry`) after adding or updating a task.

9. **Initialization and Main Loop:**
   - The `__init__` method initializes the GUI components.
   - The `__main__` block creates the main Tkinter window, instantiates the `TodoListApp` class, and starts the Tkinter main loop.

