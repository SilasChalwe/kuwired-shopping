# Kuwired Shopping Website

Kuwired is a Django-based shopping website application. This project aims to provide a seamless online shopping experience with an intuitive user interface and robust backend functionality.

## Features

- User registration and authentication
- Product listing and search
- Shopping cart functionality
- Order management
- Payment integration

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/silaschalwe/kuwired.git
    ```

2. Navigate to the project directory:
    ```bash
    cd kuwired
    ```

3. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Apply the migrations:
    ```bash
    python manage.py migrate
    ```

6. Create a superuser to access the admin panel:
    ```bash
    python manage.py createsuperuser
    ```

7. Run the development server:
    ```bash
    python manage.py runserver
    ```

8. Open your web browser and go to `http://127.0.0.1:8000/` to see the website in action.

## License

This project is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the license terms.

Under the following terms:

- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
