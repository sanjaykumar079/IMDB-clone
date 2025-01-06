# IMDB REST API Clone

A fully functional **IMDB REST API Clone** developed using **Django Rest Framework (DRF)**. This project demonstrates the implementation of a robust and scalable backend for managing movies, actors, genres, and user ratings.

## Features

### Core API Functionality
- **CRUD Operations**: Endpoints for creating, reading, updating, and deleting movies, actors, genres, and ratings.
- **Secure Authentication**: JWT-based authentication to ensure secure access.
- **Role-based Permissions**: Restricted access to sensitive operations based on user roles.

### Advanced API Features
- **Throttling**: Limiting excessive API usage to ensure optimal server performance.
- **Filtering**: Query-based filtering for searching and retrieving data efficiently.
- **Pagination**: Simplified navigation through large datasets.
- **Automated Testing**: Comprehensive test cases to ensure API stability and reliability.

### Modular Architecture
- Structured code with clear separation of views, serializers, and routers for scalability and maintainability.

## Tech Stack
- **Backend**: Django, Django Rest Framework
- **Authentication**: JSON Web Tokens (JWT)
- **Database**: SQLite (or PostgreSQL for production-ready setups)
- **Testing Tools**: Postman, Django Test Framework

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/imdb-rest-api-clone.git
   ```
2. Navigate to the project directory:
   ```bash
   cd imdb-rest-api-clone
   ```
3. Set up a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate   # For Windows
   ```
4. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Apply migrations:
   ```bash
   python manage.py migrate
   ```
6. Run the development server:
   ```bash
   python manage.py runserver
   ```
7. Access the API:
   Visit `http://127.0.0.1:8000/` in your browser or API testing tool (e.g., Postman).

## API Endpoints

| HTTP Method | Endpoint               | Description                  |
|-------------|------------------------|------------------------------|
| GET         | `/movies/`            | List all movies             |
| POST        | `/movies/`            | Create a new movie          |
| GET         | `/movies/<id>/`       | Retrieve movie details      |
| PUT         | `/movies/<id>/`       | Update a movie              |
| DELETE      | `/movies/<id>/`       | Delete a movie              |

Additional endpoints for actors, genres, and ratings follow a similar structure.

## Screenshots
Include screenshots of your API responses or Postman collections to showcase functionality.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Special thanks to the **Udemy Django REST Framework Course** for foundational guidance.

