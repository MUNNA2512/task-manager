# Task Manager

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-0.1.0-orange)

Welcome to the Task Manager project! This application allows you to manage tasks efficiently with features like adding, removing, updating, and listing tasks.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- Add, remove, update, and list tasks
- Categorize tasks
- Set priorities and due dates
- Save tasks to a file
- Load tasks from a file

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/task_manager.git
   ```
2. Navigate to the project directory:
   ```bash
   cd task_manager
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the task manager script to manage your tasks:
```bash
python task_manager/task_manager.py
```

## Examples
```python
from task_manager.task import Task
from task_manager.task_manager import TaskManager

manager = TaskManager()
manager.add_task(Task("Buy groceries", "Personal", "high", "2023-12-01"))
manager.list_tasks()
manager.save_tasks("tasks.txt")
```

## Testing
Run the tests using:
```bash
python -m unittest discover tests
```

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions, please contact [your email].

---

### Contributors
- [Your Name](https://github.com/yourusername)

### Screenshots
![Task Manager Screenshot](https://via.placeholder.com/800x400.png?text=Task+Manager+Screenshot) 