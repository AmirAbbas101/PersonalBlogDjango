# PersonalBlogDjango

PersonalBlogDjango is a feature-rich blog website built using Django. It offers functionalities such as user authentication, post creation, editing, and commenting, all presented with a clean and responsive design.

## Features

- **User Authentication**: Secure user registration and login capabilities.
- **Post Management**: Create, edit, and delete blog posts with ease.
- **Commenting System**: Engage readers through a built-in commenting feature.
- **Responsive Design**: Ensures optimal viewing experience across various devices.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/AmirAbbas101/PersonalBlogDjango.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd PersonalBlogDjango
   ```

3. **Create and Activate a Virtual Environment**:

   ```bash
   python -m venv env
   # On Windows
   env\Scripts\activate
   # On macOS/Linux
   source env/bin/activate
   ```

4. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

5. **Apply Migrations**:

   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

6. **Create a Superuser**:

   ```bash
   python manage.py createsuperuser
   ```

7. **Collect Static Files**:

   ```bash
   python manage.py collectstatic
   ```

8. **Run the Development Server**:

   ```bash
   python manage.py runserver
   ```

Visit `http://localhost:8000` in your web browser to access the application.

## Usage

- **Admin Panel**: Access the Django admin interface at `http://localhost:8000/admin` using the superuser credentials.
- **Create Posts**: Logged-in users can create new blog posts from the dashboard.
- **Commenting**: Readers can comment on posts to engage in discussions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the Django community and all contributors to this project.

---

For any inquiries or support, please contact [AmirAbbas](https://github.com/AmirAbbas101).
