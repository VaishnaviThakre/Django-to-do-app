# Django To-Do App

Welcome to the Django To-Do App repository! This project is a simple and efficient to-do list application built using the Django framework. It allows users to manage their daily tasks efficiently with features to add, edit, and delete tasks.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Task Management**: Add, edit, and delete tasks.
- **Task Categorization**: Organize tasks into different categories.
- **Responsive Design**: User-friendly interface across devices.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or higher
- Django 3.2 or higher
- Git

## Installation

1. **Clone the repository:**

   ```sh
   git clone git@github.com:VaishnaviThakre/Django-to-do-app.git
   cd Django-to-do-app
   ```

2. **Create and activate a virtual environment:**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**

   ```sh
   pip install -r requirements.txt
   ```

4. **Apply migrations:**

   ```sh
   python manage.py migrate
   ```

## Running the Application

To run the application locally, execute:

```sh
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your web browser to see the application in action.

## Usage

1. **Register an account** if you don’t have one.
2. **Log in** using your credentials.
3. **Create, edit, and delete tasks** as per your requirements.
4. **Categorize tasks** to organize them better.
5. **Set priority levels** to highlight important tasks.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch** (`git checkout -b feature/your-feature-name`).
3. **Make your changes** and commit them (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature-name`).
5. **Create a Pull Request**.

Please ensure your code adheres to the project's coding standards and includes relevant tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


Thank you for checking out the Django To-Do App! Happy task managing! 🎉
