# EventEcho - Concert Booking App

EventEcho is a concert booking application that allows users to browse available concerts, book tickets, and manage their bookings. The app is built using Django for the backend (with SQLite as the database) and React for the frontend.

## Features

- User authentication (signup, login, logout)
- Browse available concerts
- Book tickets for concerts (with a limit per user)
- View and manage bookings
- Admin panel for managing concerts

## Technologies Used

### Backend (Django)
- Django Rest Framework (DRF)
- SQLite (Default database)
- Django Authentication

### Frontend (React)
- React with Redux for state management
- Axios for API requests
- React Router for navigation

## Installation and Setup

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/EventEcho.git
   cd EventEcho
   ```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Run database migrations:
   ```sh
   python manage.py migrate
   ```

5. Create a superuser (for admin access):
   ```sh
   python manage.py createsuperuser
   ```

6. Start the backend server:
   ```sh
   python manage.py runserver
   ```

### Frontend Setup

1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the frontend development server:
   ```sh
   npm start
   ```

## API Endpoints

| Method | Endpoint               | Description               |
|--------|------------------------|---------------------------|
| POST   | `/api/signup/`         | User registration         |
| POST   | `/api/login/`          | User login               |
| POST   | `/api/logout/`         | User logout              |
| GET    | `/api/api_retrieve/`   | Retrieve concerts        |
| POST   | `/api/book-ticket/<pk>/` | Book a concert ticket |

## Updating the Project on GitHub Daily

1. Check for changes:
   ```sh
   git status
   ```

2. Add all modified files:
   ```sh
   git add .
   ```

3. Commit changes with a message:
   ```sh
   git commit -m "Updated frontend and backend features"
   ```

4. Push changes to GitHub:
   ```sh
   git push origin main  # or "master" depending on your branch
   ```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Let me know if you need any modifications or additional details!

