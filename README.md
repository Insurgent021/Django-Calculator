# Django Calculator Project

## Table of Contents

- Introduction
- Features
- Installation
- Usage
- Running Tests
- Project Structure
- Technologies Used
- Contributing
- License
- Contact

## Introduction

Welcome to the Django Calculator project! This is a simple web-based calculator built using Django. It supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- User-friendly web interface.
- Error handling for invalid inputs and division by zero.

## Installation

To get a copy of this project up and running on your local machine, follow these steps:

### Prerequisites

- Python 3.8 or higher
- Django 3.2 or higher
- pip (Python package installer)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/django-calculator.git
   cd django-calculator
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run migrations:

   ```bash
   python manage.py migrate
   ```

5. Start the development server:

   ```bash
   python manage.py runserver
   ```

6. Open your web browser and go to `http://127.0.0.1:8000` to use the calculator.

## Usage

- Enter the numbers and select the operation you want to perform.
- Click on the `Submit` button to get the result.
- The result will be displayed on the same page.

## Running Tests

To run the tests for this project, use the following command:

```bash
python manage.py test
```

## Project Structure

```
django-calculator/
├── calculator/
│   ├── migrations/
│   ├── templates/
│   │   └── calculator/
│   │       └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── django_calculator/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── requirements.txt
└── README.md
```

## Technologies Used

- [Django](https://www.djangoproject.com/) - The web framework used
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) - For creating the web interface
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - For styling the web interface
- [SQLite](https://www.sqlite.org/index.html) - Default database for development

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- Shivam Rathod - shivamrathod145@gmail.com
- [https://github.com/Insurgent021/](https://github.com/insurgent021)
- https://www.linkedin.com/in/shivamrathod021/
