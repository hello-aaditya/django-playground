```markdown
# Movies Django Project

## Overview

This Django project is a simple movie management application where users can view, add, and delete movies. 

## Features

- **Home Page**: Displays a welcome message.
- **Movies List**: Lists all movies with links to details.
- **Movie Details**: Displays details of a single movie.
- **Add Movie**: Allows users to add new movies.
- **Delete Movie**: Allows users to delete existing movies.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/hello-aaditya/django-playground
   ```

2. **Create and activate a virtual environment**:
   (This below command is only for linux user)
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Apply migrations**:
   ```bash
   python manage.py migrate
   ```

4. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

5. **Navigate to** `http://127.0.0.1:8000/` in your browser to use the application.

## File Structure

- `movies/`
  - `migrations/`: Database migrations
  - `templates/`
    - `movies/`
      - `add.html`: Form for adding a new movie
      - `detail.html`: Detail view for a single movie
      - `movies.html`: List view of all movies
  - `models.py`: Defines the Movie model
  - `views.py`: Contains the view functions for handling requests
- `urls.py`: URL routing for the project

## Code Snippets

### URLs Configuration (`urls.py`)

Routes URLs to view functions.

### Views (`views.py`)

Defines view functions to handle requests and render templates.

### Templates

- **`add.html`**: Form for adding a new movie.
- **`detail.html`**: Displays details of a specific movie.
- **`movies.html`**: Lists all movies.

### Model (`models.py`)

Defines the `Movie` model with fields for title and year.

## Contributing

Feel free to submit issues and pull requests. Ensure your changes are well-documented and tested.
