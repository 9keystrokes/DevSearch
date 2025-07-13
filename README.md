![DevSearch Logo](static/images/logo.svg)

## 🚀 Overview

DevSearch is a platform that connects developers and showcases projects. It allows developers to create profiles, share their projects, and engage with the developer community. Built with Django, HTML, CSS, and JavaScript, DevSearch offers a robust feature set for developer networking and project discovery.

## 🌐 Live Demo
Visit our platform at: [DevSearch](https://devsearch-project.onrender.com/)

## ✨ Features

- **User Authentication**: Secure login, registration, and authentication system
- **Developer Profiles**: Create and customize developer profiles with skills, bio, and contact information
- **Project Showcase**: Upload and share projects with descriptions, tags, and demo links
- **Project Rating & Reviews**: Community feedback system for projects
- **Search Functionality**: Find developers and projects based on skills and keywords
- **Messaging System**: Connect with other developers through an in-platform messaging system

## 🛠️ Tech Stack

- **Backend**: Python (Django)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL (with SQLite for development)
- **Static Files**: Django Whitenoise
- **Deployment**: Configured for Heroku

## 📋 Project Structure

```
DevSearch/
├── devsearch/            # Main Django project settings
├── projects/             # Projects app (project showcase functionality)
├── users/                # Users app (authentication and profiles)
├── static/               # Static files (CSS, JavaScript, Images)
├── templates/            # HTML templates
├── manage.py             # Django management script
└── requirements.txt      # Project dependencies
```

## 🔧 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/9keystrokes/DevSearch.git
   cd DevSearch
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run migrations**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (admin)**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server**
   ```bash
   python manage.py runserver
   ```

7. **Access the application**
   - Development server: [http://localhost:8000](http://localhost:8000)
   - Admin interface: [http://localhost:8000/admin](http://localhost:8000/admin)

## 🌐 Deployment

The project is configured for deployment on Render/Vercel with the following:
- PostgreSQL database
- Whitenoise for static files
- Gunicorn as the production web server

---

Built with ❤️ by [9keystrokes](https://github.com/9keystrokes)
