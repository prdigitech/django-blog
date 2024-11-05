
# Django Blog Application

Welcome to the **Django Blog Application**! This project is a simple and elegant blogging platform built using **Django**, **HTML**, and styled with the minimalist [Simple.css](https://simplecss.org).

---

## Features

- **Create, read, update, and delete blog posts**
- **Responsive and clean design** using [Simple.css](https://cdn.simplecss.org/simple.min.css)
- **User-friendly interface** for an enjoyable writing and reading experience

---

## Installation

### Prerequisites

- **Python 3.6+** installed on your system
- **Django** installed in your environment

### Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/PratikRamdasi/django-blog.git
   ```
   Navigate into the project folder:
   ```bash
   cd django-blog
   ```

2. **Set up a virtual environment**:
   ```bash
   python3 -m venv venv
   ```
   Activate the virtual environment:
   - On **Linux/macOS**:
     ```bash
     source venv/bin/activate
     ```
   - On **Windows**:
     ```bash
     venv\Scripts\activate
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
   Make sure to have a `requirements.txt` file with your project's dependencies listed.

4. **Run database migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser** (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

   Visit **http://localhost:8000** in your browser to access the blog.

---

## Usage

1. **Create posts**: Log in as an admin to create new blog posts.
2. **Edit or delete posts**: Manage your posts easily from the admin panel or through the user interface.
3. **Read posts**: Visitors can browse all posts in a simple and clean layout.

---

## Styling

The application uses **Simple.css** for styling, making the design minimalist and easy to maintain. The CSS file is linked directly from a CDN:
```html
<link rel="stylesheet" href="https://cdn.simplecss.org/simple.min.css">
```

---

## Screenshots

> Include some screenshots of your app if possible for a better presentation.

---

## Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

---

## License

This project is licensed under the **MIT License**.

---

## Contact

- **Author**: Pratik Pawan Ramdasi
- **Email**: [pratikramdasi321@gmail.com](mailto:pratikramdasi321@gmail.com)

---

Thank you for checking out the Django Blog Application! Enjoy writing and sharing your thoughts!
```
