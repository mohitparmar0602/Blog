# Blogg ✦

Blogg is a modern, minimalist blogging platform built with Flask. It features a clean light-themed design with vibrant green accents, Markdown support, and a robust tagging system.

![Brand](https://img.shields.io/badge/Blogg-10b981?style=for-the-badge)
![Flask](https://img.shields.io/badge/Flask-3.0.3-black?style=for-the-badge&logo=flask)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952b3?style=for-the-badge&logo=bootstrap)

## ✨ Features

- 📝 **Markdown Support**: Write posts using Markdown and see live previews.
- 🎨 **Modern Design**: Clean white theme with green accents and smooth hover effects.
- 🏷️ **Tagging System**: Organize your posts with customizable tags.
- 👤 **User Authentication**: Secure login and registration system with role-based access (Reader, Author, Admin).
- 📱 **Responsive Layout**: Fully responsive design that works on all devices.
- 🛠️ **Admin Dashboard**: Manage users and posts efficiently.

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd blogg
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**
   The application uses SQLite. The database will be automatically created on the first run.

5. **Run the application**
   ```bash
   python run.py
   ```
   The application will be available at `http://127.0.0.1:5000`.

## 🛠️ Tech Stack

- **Backend**: Flask
- **Database**: SQLite (SQLAlchemy ORM)
- **Frontend**: Bootstrap 5, Vanilla CSS
- **Editor**: Markdown2
- **Icons**: Bootstrap Icons

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
