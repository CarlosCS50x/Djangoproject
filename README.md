# Django First Blog

Welcome to my Django First Blog project! This is a simple blog application built using Django framework.

## Overview

This project aims to provide a basic blogging platform where users can create, read, update, and delete blog posts. It's a great starting point for beginners learning Django and web development.

## Features

- MySql instead of running on sqlite3.
- User authentication: Users can sign up, log in, and log out.
- CRUD operations: Users can create, read, update, and delete blog posts.
- Responsive design: The application is designed to be responsive and work well on different screen sizes.

## Technologies Used

- Python
- Django
- MySQL

## Installation

Clone the repository:

```bash
git clone https://github.com/CarlosCS50x/Djangoproject.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Set up MySQL database:
- Make sure you have MySQL installed and running.
- Create a MySQL database for the project.
- Update the database settings in `settings.py` to use your MySQL database instead of SQLite3.

Apply migrations:

```bash
python manage.py migrate
```

Run the development server:

```bash
python manage.py runserver
```

Access the application in your web browser at `http://localhost:8000/admin`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.




