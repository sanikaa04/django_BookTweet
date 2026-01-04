# BookTweet

A Django-based social media platform for sharing tweets with photo uploads. Features include user registration and authentication, tweet creation/editing/deletion, and a responsive Bootstrap UI.

## Features

- User registration and login
- Create, edit, and delete tweets
- Upload photos with tweets
- Responsive design with Bootstrap
- User authentication and session management

## Technologies Used

- Django 5.2
- Python 3.11
- Bootstrap 5
- SQLite (for development)

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sanikaa04/django_BookTweet.git
   cd django_BookTweet
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations:**
   ```bash
   cd booktweet
   python manage.py migrate
   ```

5. **Create a superuser (optional):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the application:**
   - Open your browser and go to `http://127.0.0.1:8000/`
   - Register a new account or login
   - Start creating tweets!

## Project Structure

```
booktweet/
├── booktweet/          # Main Django project settings
├── tweet/              # Tweet app with models, views, forms
├── templates/          # HTML templates
├── media/              # Uploaded photos
├── static/             # Static files (CSS, JS)
├── db.sqlite3          # SQLite database
└── manage.py           # Django management script
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the [MIT License](LICENSE).