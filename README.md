# Django Comment System

## Overview
This is a Django-based comment system that allows users to leave comments and view existing comments. The project is currently under development.

## Features (Planned)
- Users can submit comments.
- Comments are displayed in a structured manner.
- Basic moderation functionalities (e.g., deleting inappropriate comments).
- User authentication (optional).

## Installation
### Prerequisites
- Python 3.x
- Django

### Steps
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd django-comment-system
   ```
2. Create a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```
6. Open your browser and go to `http://127.0.0.1:8000/`.

## Usage
- Navigate to the main page to view comments.
- Submit a comment using the form.

## Development Status
This project is still in progress. More features and improvements will be added soon.

## Author
Developed by Richie Sayer
