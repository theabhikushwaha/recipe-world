# recipe-world
A recipe sharing web app built with Django. Users can post their own recipes,
like other people's recipes, and leave comments.

## Features
- User signup, login, and logout
- Add, edit, and delete your own recipes (with photo upload)
- Like and unlike recipes
- Comment on recipes
- Search and filter recipes by category

## Tech stack
- Python, Django
- SQLite (development)
- Bootstrap
- Pillow (image uploads)

## Getting started

1. Clone the repo
   git clone https://github.com/theabhikushwaha/recipe-share-django.git
   cd recipe-share-django

2. Create a virtual environment and install dependencies
   python -m venv venv
   source venv/bin/activate    (Windows: venv\Scripts\activate)
   pip install -r requirements.txt

3. Run migrations and start the server
   python manage.py migrate
   python manage.py runserver

4. Open http://127.0.0.1:8000

## Screenshots

## Roadmap
- [ ] Ratings
- [ ] Follow other users
- [ ] REST API

## License
MIT
