# Late Show API Challenge

## Overview
This project is a Flask-based API for managing late show data including users, guests, episodes, and appearances.

## Features
- User authentication and management
- Guest and episode data handling
- Database migrations with Flask-Migrate
- API endpoints for CRUD operations

## Setup
1. Clone the repository
2. Create a virtual environment and activate it
3. Install dependencies from requirements.txt
4. Set environment variable: `export FLASK_APP=server/app.py`
5. Initialize and upgrade the database:
   ```
   flask db init
   flask db migrate -m "initial migration"
   flask db upgrade
   ```
6. Run the Flask app:
   ```
   flask run
   ```

## Testing
Critical-path testing has been performed on database migrations and basic API functionality.

## License
Specify your license here.

