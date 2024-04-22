Project: API and Python Scripting
This project involves using Python scripting to work with an API to access employee data and organize the data into different formats. The tasks involve fetching employee to-do list data from the JSONPlaceholder API and exporting it to different data formats.

Tasks
Task 0: Gather data from an API
Write a Python script that takes an employee ID as input and fetches the corresponding user information and to-do list from the JSONPlaceholder API.
Display the employee's to-do list progress, including the employee's name, number of completed tasks, total tasks, and titles of completed tasks.
Task 1: Export to CSV
Extend the script from Task 0 to export data to a CSV file.
Export all tasks owned by the employee in the format "USER_ID","USERNAME","TASK_COMPLETED_STATUS","TASK_TITLE".
Save the file as USER_ID.csv.
Task 2: Export to JSON
Extend the script from Task 0 to export data to a JSON file.
Export all tasks owned by the employee in the format { "USER_ID": [{"task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS, "username": "USERNAME"}, ... ]}.
Save the file as USER_ID.json.
Requirements
The project should use Python 3 and follow PEP8 style guidelines.
Use urllib or requests modules to work with the API.
Follow Pythonic naming conventions for variables, functions, and classes.
Ensure scripts are executable and files end with a new line.
Add documentation to all modules and follow the specified format for data outputs.
