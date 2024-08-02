
# Kuwired Shopping Website Application

This is the official repository for the Kuwired Shopping Website Application, developed using Django.

## Features

- User-friendly interface for shopping.
- Product management for administrators.
- Secure user authentication and authorization.
- Advanced search and filtering options.
- Responsive design for optimal viewing on different devices.

## Installation

To install and run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/silaschalwe/kuwired.git
   cd kuwired
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply the migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the application:**
   Open your web browser and go to `http://127.0.0.1:8000/`.

## Configuration

Ensure you have a `.env` file in your project root with the following settings:

```
DEBUG=on
SECRET_KEY=your_secret_key
DATABASE_URL=your_database_url
ALLOWED_HOSTS=127.0.0.1, .localhost
```

## Contributing

1. **Fork the repository:**
   Click the "Fork" button on the top right of the repository page.

2. **Clone your forked repository:**
   ```bash
   git clone https://github.com/your-username/kuwired.git
   cd kuwired
   ```

3. **Create a branch for your feature:**
   ```bash
   git checkout -b feature-name
   ```

4. **Make your changes and commit them:**
   ```bash
   git add .
   git commit -m "Add some feature"
   ```

5. **Push your changes to your forked repository:**
   ```bash
   git push origin feature-name
   ```

6. **Create a pull request:**
   Go to the original repository and click the "New Pull Request" button.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## .gitignore

```
# Python
*.pyc
*.pyo
__pycache__/
env/

# Django
*.log
*.pot
*.pyc
*.pyo
__pycache__/
local_settings.py
db.sqlite3
/static

# macOS
.DS_Store

# Windows
Thumbs.db
ehthumbs.db
```

## Contact

For any inquiries or support, please contact Silas Chalwe at mchalwesilas@gmail.com or silaschalwe@outlook.com.

---

Developed by Silas Chalwe. All rights reserved.
