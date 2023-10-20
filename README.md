# TaskApp
Minimal Multi-User Task Management System
---


## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before using TaskApp, ensure you have the following prerequisites:

- Python 3.x: You can download Python from the official website: [python.org](https://www.python.org/downloads/).
- MySQL Server: You need a running MySQL server where TaskApp will store task data. Make sure you have the necessary MySQL server and connection details.
- pip: The Python package manager, `pip`, is required for installing Python dependencies.
## Installation

1. Clone or download the TaskApp repository to your local machine.

2. Install the required Python libraries by running the following command within the project directory:

   ```bash
   pip install -r requirements.txt


## Usage

- **Starting the Application:**
  - Run `taskapp.py` to start the application.
  - You will be prompted to enter your MySQL username and password. The application will create a 'taskapp' database and necessary tables if they don't exist.

- **Main Menu:**
  - The main menu displays your tasks in a tabular format.
  - You can choose options to add tasks, delete tasks, update task status, or exit the application.

- **Adding a Task:**
  - Choose 'a' from the main menu to add a new task.
  - Enter the task name, description, status, and priority.

- **Deleting a Task:**
  - Choose 'd' from the main menu to delete a task by its TaskID.
  - Specify the TaskID of the task you want to delete.

- **Updating Task Status:**
  - Choose 'u' from the main menu to update the status of a task by its TaskID.
  - Specify the TaskID and the new status (Not Started, In Progress, Completed).

- **Exiting the Application:**
  - Choose 'e' from the main menu to exit the application.

## Features

- Create, update, and delete tasks with attributes like name, description, status, and priority.
- Displays tasks in a tabular format for easy management.
- Provides error handling and validation for user inputs.
- Allows multiple users to maintain tasks.

## Contributing

If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Create a pull request with a clear description of your changes.

## License

This project is licensed under the [MIT License](LICENSE).
