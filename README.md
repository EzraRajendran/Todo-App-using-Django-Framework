# Todo App using Django Framework

## Overview

This **Todo App** is a simple web-based application built using the Django framework. It allows users to manage their tasks effectively by adding, editing, deleting, and marking tasks as complete. The project is designed to showcase the fundamental features of Django, including CRUD (Create, Read, Update, Delete) operations and user authentication.

## Features

- **Add Tasks**: Users can add new tasks to their list.
- **Edit Tasks**: Modify existing tasks with ease.
- **Mark as Complete**: Users can mark tasks as complete when done.
- **Delete Tasks**: Remove tasks that are no longer needed.
- **User Authentication**: Users can register, log in, and manage their tasks securely.
- **Responsive Design**: The app works well on both desktop and mobile devices.

## Technology Stack

- **Framework**: Django 4.x
- **Frontend**: HTML, CSS, Bootstrap (for responsive design)
- **Backend**: SQLite (Django’s default database)
- **Languages**: Python (Django), HTML, CSS
- **Version Control**: Git

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/EzraRajendran/Todo-App-using-Django-Framework.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Todo-App-using-Django-Framework
   ```

3. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

4. **Activate the virtual environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On Linux/Mac:
     ```bash
     source venv/bin/activate
     ```

5. **Install the dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

6. **Run database migrations**:
   ```bash
   python manage.py migrate
   ```

7. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

8. **Access the app**:
   Open your browser and go to `http://127.0.0.1:8000/`.

## How to Use

- **Home**: View all tasks.
- **Add Task**: Add a new task by entering the task description and due date.
- **Edit Task**: Edit the task details by clicking on the task.
- **Mark as Complete**: Mark tasks as complete by clicking the checkbox next to the task.
- **Delete Task**: Delete tasks by clicking the delete button.

## File Structure

- `todo/`: Contains the core application code.
- `templates/`: HTML templates for the app.
- `static/`: CSS and JS files for the frontend.
- `db.sqlite3`: SQLite database for storing tasks.
- `requirements.txt`: Python dependencies.

## Future Improvements

- Add priority levels for tasks.
- Implement task categorization.
- Add reminders and due date notifications.
- ![image](https://github.com/user-attachments/assets/8c1bfeed-a217-42dc-bd1c-e5a19c6f5031)


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
