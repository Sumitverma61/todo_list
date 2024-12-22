# ToDo Web App

A simple and elegant ToDo web application built using the Flask framework, styled with Tailwind CSS, and powered by SQLite for data storage.

## Features

- **User-friendly Interface**: A clean and modern design using Tailwind CSS.
- **Task Management**: Create, update, mark as complete, and delete tasks.
- **Persistent Storage**: Store tasks locally with SQLite database integration.
- **Responsive Design**: Optimized for desktop and mobile devices.

## Technology Stack

- **Backend**: [Flask](https://flask.palletsprojects.com/) - A lightweight Python web framework.
- **Frontend**: [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for styling.
- **Database**: [SQLite](https://www.sqlite.org/index.html) - A lightweight and embedded database.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.7 or above
- SQLite installed on your system

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/todo-web-app.git
    cd todo-web-app
    ```

2. **Set up the virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows, use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database**:
    ```bash
    flask db init
    flask db migrate
    flask db upgrade
    ```

5. **Run the application**:
    ```bash
    flask run
    ```

6. Open your browser and navigate to `http://127.0.0.1:5000/`.




