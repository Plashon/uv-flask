# My Flask App

A Flask web application with user management APIs, created with uv.

## Project Structure

- `app.py` - Main Flask application with user management APIs
- `main.py` - Simple entry point script
- `test_api.py` - API tests using requests
- `pyproject.toml` - Project dependencies and metadata
- `uv.lock` - Locked dependencies
- `report/` - Test reports directory

## API Endpoints

- `POST /users` - Create a new user
- `GET /users/<id>` - Get a user by ID
- `DELETE /users/<id>` - Delete a user by ID

## Setup

1. Install dependencies:
   ```
   uv sync
   ```

2. Run the application:
   ```
   uv run python app.py
   ```

3. Run tests:
   ```
   uv run pytest
   ```

## Dependencies

- Flask - Web framework
- requests - HTTP library for testing
- pytest - Testing framework
- pytest-html - HTML test reports

The application will start on `http://127.0.0.1:5000` by default.